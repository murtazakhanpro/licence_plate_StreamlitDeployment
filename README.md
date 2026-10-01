# Licence Plate Detection

A Streamlit app that runs the bundled Ultralytics YOLO model on an uploaded image.

## Run locally

```bash
pip install -r requirements.txt
streamlit run app1.py
```

The model file `licence_plate_model.pt` must remain in the repository root.

## Deploy on Streamlit Community Cloud

1. Sign in to [Streamlit Community Cloud](https://share.streamlit.io/) with the GitHub account that can access this repository.
2. Select **Create app** and choose `murtazakhanpro/licence_plate_StreamlitDeployment` on the `main` branch.
3. Set the app file path to `app1.py`, then deploy.
