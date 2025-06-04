# How to use local python based install

1. Git clone repo [https://github.com/icloud-photos-downloader/icloud_photos_downloader](https://github.com/icloud-photos-downloader/icloud_photos_downloader) <br>
2. Review the overall instructions on the repo
2. Create Python venv (virtual environment) This was tested with Python 3.13 <br>
3. Activate venv, install python packages with `python -m pip install -r requirements.txt` <br>
4. Check icloud photo storage used on iCloud <br>
5. Identify a local disk and path which has enough space to store your entire iCloud photos, make note of the path <br>
5. Get your icloud userid and password handy <br>
5. From the terminal, navigate to the project directory - check that your authorization works: `icloudpd --username my@email.address --password my_password --auth-only`<br>
6. When ready, run icloudpd to download your photos, with: `icloudpd --directory /data --username my@email.address --password my_password` <br>
