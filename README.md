# URDF-Exporter-for-ROS-2-Gazebo-Classic-
This is a URDF Exporter for ROS 2 that integrates with Autodesk Fusion 360 to generate URDF files for use with Gazebo Classic.  It allows you to directly export your Fusion 360 models into URDF format, making it easier to simulate them in ROS 2 environments.


📂 Installation

Download / Clone this repository

On GitHub, click Code > Download ZIP, or clone it:

git clone https://github.com/<your-username>/URDF_Exporter_Ros2.git


Locate the Fusion 360 Scripts folder
Paste the folder URDF_Exporter_Ros2 into the following directory:

C:\Users\<YourUsername>\AppData\Roaming\Autodesk\Autodesk Fusion 360\API\Scripts


⚠️ Replace <YourUsername> with your actual Windows username.

Example:

C:\Users\Admin\AppData\Roaming\Autodesk\Autodesk Fusion 360\API\Scripts


Restart Fusion 360

Open Fusion 360.

Go to Tools > Scripts and Add-ins.

You should now see URDF_Exporter_Ros2 listed.

▶️ Usage

Open your 3D model in Fusion 360.

Launch the script from Scripts and Add-ins.

Configure your URDF export options (links, joints, materials, etc.).

Export the URDF package.

Place the generated URDF in your ROS 2 workspace under a description package.

⚙️ Requirements

Autodesk Fusion 360 (with API enabled)

ROS 2 (tested with Humble / Iron)

Gazebo Classic

📌 Notes

This exporter is tailored for Gazebo Classic (not Ignition Gazebo).

Exported URDFs may require manual edits for complex assemblies.

Contributions and improvements are welcome — feel free to open pull requests!

📜 License

MIT License. Free to use and modify.
