<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="f5k2qky5i"/><path class="osdx_g80h"/><path class="w893lsxcp"/><path class="q_xg20buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wester" /></template>
<style>
.f5k2qky5i {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.499px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.osdx_g80h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.719 19.75a23.4 23.4 0 0 1 8.413-14.28m.806 37.06a23.4 23.4 0 0 1-9.105-14.282");
}

.q_xg20buh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.449 25.939v-3.88h1.394c.788 0 1.427.583 1.427 1.303s-.639 1.303-1.427 1.303H29.45m1.393 0l1.394 1.273m-10.54-3.879h2.822m-1.411 3.88v-3.88m-14.818 0l1.066 3.88l1.064-3.88l1.065 3.88l1.065-3.88m5.012 3.455c.261.31.589.425 1.044.425h.63c.588 0 1.063-.433 1.063-.968v-.004c0-.535-.476-.968-1.062-.968h-.696c-.587 0-1.063-.434-1.063-.969c0-.536.477-.97 1.066-.97h.627c.455 0 .783.114 1.044.424m-6.266 1.515h1.388m.737-1.94h-2.13v3.88h2.13m9.847-1.94h1.388m.737-1.94h-2.13v3.88h2.13");
}

.w893lsxcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.154 5.499l27.202 18.5l-27.202 18.5");
}

</style>
