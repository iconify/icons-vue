<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><ellipse class="zvwwglj7e"/><path class="m7s35fb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:marco-polo" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m7s35fb3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.449 30.336c4.987-4.623 14.033-9.197 23.469-11.014M10.447 7.31c8.245.387 14.069 3.993 17.845 7.769m3.878-1.295c.287-5.305-.255-7.082-1.178-10.121m12.712 11.721c-.988-.16-4.337-.495-7.817 1.054m6.833 18.145c-.88-5.955-4.434-10.583-7.24-12.905m-5.145 1.742c-1.621 10.604-5.165 17.346-8.655 21.956");
}

.zvwwglj7e {
  cx: 31.63px;
  cy: 18.675px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.758px;
  ry: 4.931px;
}

</style>
