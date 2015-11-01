## Minimal Bootstrap Responsive Tab JS

#### Install & Usage

Include `src/responsive-tab.js` in you html head

```
<script type="text/javascript" src="./src/responsive-tab.js"></script>
```
and that's it, it will lookup for bootstrap's standard selectors `ul.nav-tabs`, `li.dropdown` && `ul.dropdown-menu` and auto init reflow of nav items.


#### Nav Tabs Sample Structure
```
<ul class="nav nav-tabs">
  <li class="active"><a href="#home" role="tab" data-toggle="tab">Home</a></li>
  <li><a href="#profile" role="tab" data-toggle="tab">Profile</a></li>
  <li><a href="#dropdown1" role="tab" data-toggle="tab">@fat</a></li>
  <li><a href="#dropdown2" role="tab" data-toggle="tab">@mdo</a></li>
  <li class="dropdown">
    <a href="#" id="myTabDrop1" class="dropdown-toggle" data-toggle="dropdown">Dropdown <span class="caret"></span></a>
    <ul class="dropdown-menu" id="myTabDrop1-contents">
    </ul>
  </li>
</ul>

<div class="tab-content">
  <div role="tabpanel" class="tab-pane active" id="home">
    <p>Etsy mixtape wayfarers</p>
  </div>
  <div role="tabpanel" class="tab-pane" id="profile">
    <p>Etsy mixtape wayfarers, ethical wes anderson tofu before they sold out</p>
  </div>
  <div role="tabpanel" class="tab-pane fade" id="dropdown1" aria-labelledby="dropdown1-tab">
    <p>Etsy mixtape wayfarers</p>
  </div>
  <div role="tabpanel" class="tab-pane fade" id="dropdown2" aria-labelledby="dropdown2-tab">
    <p>Trust fund seitan letterpress</p>
  </div>
</div>
```
