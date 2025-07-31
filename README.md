# 👨‍💻 Face\_RecognitionV1

A Python project using OpenCV and Tkinter to capture and store facial images for recognition purposes.
The GUI allows users to enter their name, capture 500 face images, and logs all data into an Excel file.

---

## 🚀 Features

* Add Face: Users can add their face to the database by clicking the "Add Face" button in the GUI.
* Real-time Face Detection: Uses OpenCV to display webcam feed and detect faces with bounding boxes.
* Data Storage: Images are stored in user-named folders inside a `faces/` directory.
* Excel Logging: Face capture actions are logged in `face_records.xlsx` with timestamp and folder path.
* Simple GUI: A lightweight interface using Tkinter for easy interaction.

---

## 📦 Requirements

Ensure you have the following installed:

* Python 3.x
* OpenCV (opencv-python)
* Pandas
* Tkinter (built-in with most Python distributions)
* openpyxl (for Excel export)

### Install with:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install opencv-python pandas openpyxl
```

Create a file named `requirements.txt` with:

```text
opencv-python
pandas
openpyxl
```

---

## 🧪 How to Use

1. Clone this repository:

```bash
git clone https://github.com/your_username/face-recognition-database.git
```

2. Navigate to the project directory:

```bash
cd face-recognition-database
```

3. Run the application:

```bash
python main.py
```

4. Click "Add Face" in the GUI and enter your name.

5. The app will capture 500 images and save them in:

```
faces/YourName/
```

6. Excel log will be saved to:

```
face_records.xlsx
```

---

## 💡 Tip

You can explore different ASCII art styles to add to the GUI experience. Visit:
🎨 [https://ascii.co.uk/art](https://ascii.co.uk/art)

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -am 'Add feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a pull request

---

## 📝 License

This project is licensed under the MIT License.
See the `LICENSE` file for more details.

Create a `LICENSE` file with:

```text
MIT License

Copyright (c) 2025 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy...
```

---

## 👨‍💻 Author

Prem Kumar Reddy.V
GitHub: https://github.com/premkumar-027
