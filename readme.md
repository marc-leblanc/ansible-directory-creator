# Ansible *"Best Practice"* Directory Structure Creator

Yes, *"Best Practice"* is subjective, and you may not need all of these  directories, but this beats creating them by hand because lets face it, at least part of why automation exists is because we are lazy when it comes to medial tasks. Enjoy!

## Usage

This currently uses no inventory and runs explicitly on localhost.

Simply specify the project path

```ansible-playbook -e "project_path=/some/path" site.yml```

Create an ansible project directory in */home/foo/bar*

```ansible-playbook -e "project_path=/home/foo/bar" site.yml```

## Next steps
This is probably the end of the road, it does what I need
