---
layout: page
title: Home
---

<div class="row justify-content-center pb-4">
  <div class="col-md-8" >
    <h2>About the {{site.title}}</h2>
    <p>This site provides the text of <em>Idaho wilderness: hearings before the Subcommittee on Public Lands and Reserved Water of the Committee on Energy and Natural Resources, United States Senate, Ninety-eighth Congress, first session, to review the Idaho wilderness recommendations</em>, 1983, broken into the individual testimonies of citizens who spoke during the hearings.</p>
    <p>The Wilderness Preservation System and Wilderness Act required federal agencies to review all roadless areas and recommend whether they ought to be protected as wilderness.
    The subsequent Roadless Area Review and Evaluation (RARE) processes (courts found the first RARE process insufficient and ordered a second, known as RARE II) conducted by the U.S. Forest Service generated an enormous archive, the largest input from citizen hearings in American history (Marsh 125). 
    Because of their unwieldy size, historians have barely examined them, relying instead on the published writings of leaders from the standard conservation organizations. </p>
    <p>
    The text is based on Google digitized copies of this public domain document. 
    The scanned copy can be found on <a href="https://catalog.hathitrust.org/Record/010021819">Hathi Trust</a>.
    The OCR text was extracted and processed to provide access to 571 testimonies from 560 individuals presented in person at the hearings in Idaho.
    </p>
    <div class="text-center">
      <a href="{{ 'about.html' | relative_url }}" class="btn btn-info btn-lg">More About the Project</a>
    </div>
  </div>
</div>
<div class="row">
  <div class="col-md-4">  
    {% include index/featured-terms.html field="profession" title="Top Subjects" btn-color="info" featured=site.data.theme.featured-subjects max=site.data.theme.featured-subjects-max %}
  </div>
  <div class="col-md-4">  
    {% include index/featured-terms.html field="place" title="Locations" btn-color="outline-secondary" featured=site.data.theme.featured-locations max=site.data.theme.featured-locations-max %}
  </div>
  <div class="col-md-4">  
    {% include index/objects.html %}
  </div>
  <div class="col-md-12">
    {% include index/data-download.html %}
  </div>
</div>