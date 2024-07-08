---
draft: false
---

<style>
  /* Responsive iframe container */
  .iframe-container {
    position: relative;
    overflow: hidden;
    padding-top: 56.25%; /* 16:9 Aspect Ratio */
    height: 0;
  }

  /* Responsive iframe */
  .iframe-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
  }

  /* Adjustments for smaller devices */
  @media only screen and (max-width: 600px) {
    .iframe-container {
      padding-top: 75%; /* Adjust for aspect ratio */
    }
  }
</style>

<div style="text-align: center;">
  <br>
  Please use the form below to provide us with your RSVP. Please submit the form for every person attending.
  <br>
  <div class="iframe-container">
    <!-- Responsive iframe -->
    <iframe src="https://form.victorianobennett.wedding/www/rsvp/" name="myiFrame" scrolling="no" frameborder="0" allowfullscreen></iframe>
  </div>
</div>



