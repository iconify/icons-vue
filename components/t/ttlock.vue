<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="defu9rb9t"/><path class="a-wx9yrbu"/><path class="l-4hii0je"/><path class="t0pmuf4pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ttlock" /></template>
<style>
.a-wx9yrbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.603 29.857l-7.192 7.191m3.143.11l-1.626-1.626m3.929 1.041l-2.486-2.485m3.199.073l-1.636-1.635m.227-13.376V9.597a2.779 2.779 0 1 0-5.557 0v11.234");
}

.defu9rb9t {
  cx: 25.097px;
  cy: 27.363px;
  r: 3.527px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l-4hii0je {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.719 16.831V7.28a2.779 2.779 0 1 0-5.558 0v12.873");
}

.t0pmuf4pe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.604 20.832v-7.943a2.779 2.779 0 1 0-5.558 0v19.263c0 6.267 5.081 11.348 11.349 11.348c3.785 0 7.137-1.853 9.199-4.702l8.808-11.646a2.779 2.779 0 1 0-4.454-3.324l-2.672 3.579V9.597a2.779 2.779 0 1 0-5.557 0v10.555");
}

</style>
