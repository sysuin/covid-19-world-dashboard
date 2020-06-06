# hello world example

Hello World application to get started building interactive dashboards with voila.

This example uses a conda `environment.yml` file to list the dependencies.

For an example using `requirements.txt`, you can check [render-stl](https://github.com/voila-gallery/render-stl) or [gaussian-density](https://github.com/voila-gallery/gaussian-density).


## Local Setup


To test the application locally:

```bash
conda env create
conda activate voila-gallery-hello-world-example

voila app.ipynb
```

This will open a new browser tab at [http://localhost:8866](http://localhost:8866) serving the dashboard.


## Testing on Binder


An environment file is all you need to make the dashboard work with Binder:

1. Go to [mybinder.org](https://mybinder.org)
2. Put the URL of the repository
3. Then select `Url` instead of `File`
4. Put the following URL in the `URL to open (optional)` field: `/voila/render/app.ipynb`

The repository is now ready to be used on [Binder](https://mybinder.org)!

More details about Binder can be found [in the documentation](https://mybinder.readthedocs.io/en/latest/introduction.html#preparing-a-repository-for-binder).

