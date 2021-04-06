<a name="HomeComponent"></a>

## HomeComponent
Component for home page.

**Kind**: global class  
**Component**:   

* [HomeComponent](#HomeComponent)
    * [.handleHideModal](#HomeComponent+handleHideModal)
    * [.handleShowModal](#HomeComponent+handleShowModal)
    * [.clearApplicationState](#HomeComponent+clearApplicationState)
    * [.newProject](#HomeComponent+newProject)
    * [.componentDidMount()](#HomeComponent+componentDidMount)
    * [.render()](#HomeComponent+render)
    * [.handleDeleteProject(projectName)](#HomeComponent+handleDeleteProject)
    * [.handleOpenProject(projectName)](#HomeComponent+handleOpenProject)

<a name="HomeComponent+handleHideModal"></a>

### homeComponent.handleHideModal
function called to hide the projects list modal

**Kind**: instance property of [<code>HomeComponent</code>](#HomeComponent)  
<a name="HomeComponent+handleShowModal"></a>

### homeComponent.handleShowModal
function called to show the projects list modal

**Kind**: instance property of [<code>HomeComponent</code>](#HomeComponent)  
<a name="HomeComponent+clearApplicationState"></a>

### homeComponent.clearApplicationState
function called to clear the state of the application

**Kind**: instance property of [<code>HomeComponent</code>](#HomeComponent)  
<a name="HomeComponent+newProject"></a>

### homeComponent.newProject
function called to create a new project

**Kind**: instance property of [<code>HomeComponent</code>](#HomeComponent)  
<a name="HomeComponent+componentDidMount"></a>

### homeComponent.componentDidMount()
A react lifecycle method called when the component did mount.

**Kind**: instance method of [<code>HomeComponent</code>](#HomeComponent)  
<a name="HomeComponent+render"></a>

### homeComponent.render()
The render function.

**Kind**: instance method of [<code>HomeComponent</code>](#HomeComponent)  
<a name="HomeComponent+handleDeleteProject"></a>

### homeComponent.handleDeleteProject(projectName)
function called to delete a project

**Kind**: instance method of [<code>HomeComponent</code>](#HomeComponent)  

| Param | Type | Description |
| --- | --- | --- |
| projectName | <code>string</code> | project name to be deleted |

<a name="HomeComponent+handleOpenProject"></a>

### homeComponent.handleOpenProject(projectName)
function called to open a project from the list

**Kind**: instance method of [<code>HomeComponent</code>](#HomeComponent)  

| Param | Type | Description |
| --- | --- | --- |
| projectName | <code>string</code> | project name to be opened |
