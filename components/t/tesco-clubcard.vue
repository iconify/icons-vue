<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="ydvga8btl"/><path class="r3ezx-bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tesco-clubcard" /></template>
<style>
.r3ezx-bcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.473 26.897h23.054M18.23 21.103h11.54");
}

.ydvga8btl {
  width: 39px;
  height: 27.56px;
  x: 4.5px;
  y: 10.22px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.5px;
  ry: 3.5px;
}

</style>
