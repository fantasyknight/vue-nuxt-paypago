<template>
    

<!-- Horizontal Steppers -->
<div class="row">
  <div class="col-md-12">

    <!-- Stepers Wrapper -->
    <ul class="stepper stepper-horizontal">

      <!-- First Step -->
      <li class="completed">
        <a href="#!">
          <span class="circle">1</span>
          <span class="label">First step</span>
        </a>
      </li>

      <!-- Second Step -->
      <li class="active">
        <a href="#!">
          <span class="circle">2</span>
          <span class="label">Second step</span>
        </a>
      </li>

      <!-- Third Step -->
      <li class="warning">
        <a href="#!">
          <span class="circle"><i class="fas fa-exclamation"></i></span>
          <span class="label">Third step</span>
        </a>
      </li>

    </ul>
    <!-- /.Stepers Wrapper -->

  </div>
</div>
<!-- /.Horizontal Steppers -->
</template>

<script>
export default {
  data:function()
  {}
}
</script>