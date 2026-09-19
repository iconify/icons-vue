<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="fi_vsxxkp"/><path class="iw1qjnbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:saikou" /></template>
<style>
.fi_vsxxkp {
  fill: none;
  stroke: currentColor;
  d: path("M18.277 42.5s14.171-8.083 14.295-13.28c.07-2.88-1.029-4.205-3.003-4.804M18.47 23.292c-2.066-.83-2.78-2.468-2.563-5.045c.337-4.013 12.127-10.264 14.002-12.747");
}

.iw1qjnbeu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.242 24.75l-3.375 1.948l-5.973 3.449a.866.866 0 0 1-1.299-.75V18.603a.866.866 0 0 1 1.3-.75l3.374 1.949l5.973 3.448a.866.866 0 0 1 0 1.5");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
