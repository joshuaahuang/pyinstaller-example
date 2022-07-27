# Quick Start

[PyInstaller documentation - Link](#https://pyinstaller.org/en/stable/#using-pyinstaller)

1. Write a working Python script

2. Generate files with pyinstaller:
`pyinstaller your_file_name.py`

3. This command will generate a *your_file_name*.spec file. Include the dll required by the application and any custom settings ([Using spec files - https://pyinstaller.org/en/stable/#using-spec-files](#https://pyinstaller.org/en/stable/#using-spec-files))

4. Once done, generate standalone binary:
`pyinstaller --onefile your_file_name.py`
