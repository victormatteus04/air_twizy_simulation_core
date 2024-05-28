# Alternatives for dependencies management

# gitman X vcstool

## Gitman:

- Designed for managing multiple Git repositories as dependencies.
- Configuration File: Uses a gitman.yml file for specifying repositories.
- Features: Allows you to specify branches, tags, or specific commits.
- Supports linking repositories into specific directories.
- Use Case: Best for projects where you need to manage multiple external Git repositories with fine-grained control over versions.
- Usege Example: [mrs_uav_core](https://github.com/ctu-mrs/mrs_uav_core/tree/master/ros_packages).

## vcstool

- Designed for ROS ecosystems but can be used for other projects.
- Configuration File: Uses a .repos file (YAML format) for specifying repositories.
- Features: Can handle multiple version control systems (Git, Mercurial, etc.). Integrates well with ROS tools.
- Use Case: Ideal for ROS projects where you need to manage dependencies from various VCS types.

## Comparison

- Ease of Use: Gitman is more straightforward for managing Git dependencies.
- vcstool is more versatile in handling different VCS.
- Integration: vcstool integrates better with ROS tools and workflows.
- Flexibility: Gitman provides more specific Git-related features.

## Recommendation

For ROS projects: Use vcstool for its integration with ROS workflows.
For non-ROS projects with Git dependencies: Gitman might be easier and more focused.

Choose based on your project’s specific needs and the type of dependencies you need to manage.