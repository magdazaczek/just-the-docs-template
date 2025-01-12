---
title: Procedure overview
layout: default
nav_order: 2
has_children: true
---



# How to manage tasks in Microsoft Project

Microsoft Project is a powerful tool for planning, organizing, and managing projects effectively. One of its core functions is task management, which helps project managers define, schedule, and track the work necessary to complete a project. This article provides a step-by-step guide to managing tasks in Microsoft Project.


## Definition of tasks

In Microsoft Project, tasks represent the individual pieces of work required to complete a project. Tasks can range from small, simple activities to large, complex deliverables. Effective task management ensures that your project stays on track, within scope, and on budget.
Each task has these properties: 

- Duration 
- Start and fend dates
- Dependencies
- Assigned resources

## Add and organize tasks

### Step 1: Open your project file

To open a project file:

1. Go to Microsoft Project.
2. Open an existing project.
3. To create a new project, click **File > New** and choose a template or leave it blank.

### Step 2: Add tasks

To add a task:

1. Go to the **Gantt Chart** view.
2. In the **Task Name** column, type the name of the task.
3. Click **Enter**.

### Step 3: Organize tasks into phases

To organize tasks into a phase:

1. Find tasks that belong to the same phase.
2. Indent tasks to create a hierarchy:
   - Select the tasks you want to group.
   - Click the **Indent Task** button under the **Task** tab.
3. The indented tasks become subtasks of a summary task, which represents the phase.

## Set task properties

### Step 4: Define durations

To specify duration for a task:

1. In the **Duration** column, specify how long each task will take.

**Example**: Enter "5d" for five days or "3h" for three hours. For tasks with uncertain durations, use "TBD" as a placeholder and update it later.

### Step 5: Set start and end dates
By default, Microsoft Project automatically schedules tasks based on the project start date.

To manually set dates:

1. Double-click the task.
2. In the **Task Information** dialog box, go to the **General** tab.
3. Enter the desired start and end dates.

### Step 6: Link tasks (dependencies)
Highlight two or more tasks that are dependent on each other.

To link tasks:

1. Click the **Link Tasks** button under the **Task** tab.
2. This creates a Finish-to-Start (FS) dependency by default (the second task starts after the first one ends).
3. To modify dependencies, double-click the link line or use the **Task Information** dialog box.


## Assign resources

### Step 7: Add resources

To add resources:

1. Select **Resource Sheet** from the **View** tab.
2. Enter the names of resources (e.g., team members, equipment) and their details.

### Step 8: Assign resources to tasks

To assign resources to tasks:

1. Go to the **Gantt Chart** view. 
2. Double-click a task to open the **Task Information** dialog. 
3. Go to the **Resources** tab.
4. Select a resource from the list and assign it to the task.
5. Click **OK** to save.


## Track progress 

### Step 9: Update task status 

To update a task status:

1. Navigate to the **Task** tab.
2. Use the **Mark on Track** button to update task progress as "On Track."
3. To specify progress: 
   - Enter a percentage in the **% Complete** column.

### Step 10: Adjust as needed
To identify delayed tasks, use the **Tracking Gantt** view. You can adjust durations, resources, or dependencies to bring the project back on track.


## Tips for better task management

**Break down large tasks:** Ensure tasks are granular enough to be manageable and trackable.

**Update regularly:** Update task progress regularly to reflect the current status.

**Monitor critical path:** Use the Critical Path Method (CPM) to focus on tasks that directly impact project deadlines.

**Communicate changes:** Notify stakeholders promptly about any task-related changes that may affect the overall project.

**Generate reports:** Use built-in reporting features to generate task summaries and share updates with your team.