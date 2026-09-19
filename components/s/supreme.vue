<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="p6gdtf1cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:supreme" /></template>
<style>
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

.p6gdtf1cf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.692 18.452l-.553 6.908c-.185 2.313 1.51 4.187 3.788 4.187s4.273-1.874 4.458-4.187l.553-6.908M10.26 27.713c.904 1.337 2.132 1.835 3.896 1.835h2.442c2.272 0 4.264-1.87 4.449-4.187s-1.507-4.187-3.78-4.187h-2.692c-2.275 0-3.969-1.872-3.784-4.185s2.183-4.189 4.463-4.189h2.428c1.764 0 2.992.498 3.897 1.835M42.5 19.292a3.8 3.8 0 0 0-2.41-.84c-2.277 0-4.273 1.875-4.458 4.187m-.217 2.722c-.185 2.312 1.51 4.187 3.788 4.187c1.278 0 2.467-.59 3.297-1.518m-6.533-9.578L34.628 35.2");
}

</style>
