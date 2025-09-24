# GraphNotes

GraphNotes is a simple graphical note-taking application with drawing capabilities. It provides a transparent window for sketching quick notes or diagrams using basic drawing tools. This application is developed with Python and utilizes libraries such as Pillow for image support and tkinter for the graphical user interface.

## Features

- Draw directly on a transparent window.
- Save your drawings as timestamped PNG files.
- Load the last saved note upon startup.
- Clear drawings with a click of a button.
- Customize various parameters like window dimensions, colors, and line settings using a configuration file.

## Installation

GraphNotes requires Python 3.8 or higher.  To set up the project, run:
    
```bash
pip install -e .
```

The command will install all necessary dependencies specified in the `pyproject.toml` file.

## Usage

GraphNotes can be launched via the command line by running:

```bash
graphnotes
```

Upon launching, you will see a semitransparent drawing window. Here are some controls:

- **Left Mouse Button**: Click and drag to draw.
- **Save Button**: Save your current drawing with a timestamp.
- **Clear Button**: Clear the current drawing canvas.
- **Exit Button**: Close the application.

## Configuration

GraphNotes uses a configuration file (`graphnotes.conf`) to manage user settings. The file is located in the `.config/graphnotes` directory within your home folder. You can adjust the following parameters:

- `ratio`: The ratio for scaling the canvas.
- `width` and `height`: Dimensions of the window.
- `bg_color`: Background color of the drawing area.
- `control_bg`, `button_bg`, `button_fg`: Colors for controls and buttons.
- `line_color`: Color of drawing lines.
- `line_width`: Thickness of drawing lines.

## Development

GraphNotes is written in Python, using the following main libraries:

- **tkinter**: Standard library for the GUI interface.
- **Pillow**: Added for advanced image handling features.
- **configparser**: Used to handle the configuration files.

Additional standard libraries include `threading`, `datetime`, `os`, and `glob`.

## License

GraphNotes is created by Francesco Mannella, and it's provided under the [your chosen license here].

---

For any questions or contributions, please contact the author at <francesco.mannella@gmail.com>.
