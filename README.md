**Python Disk Mount**
=====================

### Project Title
A Python script to dynamically mount devices by their UUIDs, making it a breeze to work with multiple disks in your development environment!

### Description
I built this to simplify the process of mounting and working with external disk images or devices. With `python-disk-mount`, you can easily attach, detach, and explore multiple disks without worrying about manual device creation and management.

**One cool feature is...**

The script automatically discovers available devices using `blkid` and creates mount points based on the UUIDs of the devices. This way, you can keep your disk images organized by their contents rather than arbitrary names!

### Features
- **Automatic Device Discovery**: Find available devices using `blkid` without manual configuration.
- **UUID-Based Mount Points**: Create mount points based on device UUIDs for easy identification and organization.
- **Dynamic Mounting and Unmounting**: Attach and detach disks with ease, ensuring your workspace remains clutter-free.

### Installation
1. **Prerequisites**:
	* Python 3.x (preferably the latest version)
2. **Installation Instructions**:
```bash
git clone https://github.com/hasnocool/python-disk-mount.git
cd python-disk-mount
pip install -r requirements.txt
```
This will fetch and install any required dependencies.

### Usage

1. Run `python mount.py` to start the script.
2. The script will automatically discover available devices using `blkid`.
3. Based on UUIDs, it will create corresponding mount points and attach the disks.
4. Use your new mounts as you would any other disk (e.g., copy files, run applications).
5. When finished, simply detach (unmount) each device to free up space.

### Contributing

If you'd like to contribute or have suggestions on how to improve this project, feel free to:

1. Fork the repository.
2. Make your changes and commit them with meaningful messages.
3. Create a pull request detailing what you've changed.

I'm always excited about new ideas and improvements!

### License
This project is licensed under [MIT License](https://opensource.org/licenses/MIT).

### Tags/Keywords

- Python Scripting
- Disk Management
- UUID-Based Mount Points
- Automatic Device Discovery
- Dynamic Mounting and Unmounting