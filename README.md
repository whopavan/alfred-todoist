# Alfred Todoist Workflow
Create todoist tasks easily directly from your alfred. It's lite and you can create tasks by using natural language date time.

![alfred-todoist](https://github.com/whopavan/alfred-todoist/blob/master/src/preview.png?raw=true)

## How to install
To install you must be a alfred power user (which supports workflows).
- Go to [releases](https://github.com/whopavan/alfred-todoist/releases) and download the latest binary file (one with `.alfredworkflow` at the end)
- Once downloaded double click on the binary and it should install

Note: Before it installs, you have to provide your todoist API token when asked, you can get yours from [here](https://todoist.com/app/settings/integrations).

### More about Natural language date time
Basic natural language date time like "...tomorrow at 8 am", "...next monday", "...every week", "...next weekend" should be identified. Though easy to break if you intend to (its a simple regex looking for texts like "tomorrow", week days name, am, pm etc).

`Natural language date time is not perfect but will update as much as I can to make it better.`<br>
Also feel free to contribute 🙂

## Known Issues
- Can only create task (delete, edit etc not supported).
- Natural language date time isn't perfect.
- No feedback to user if task creation fails.
