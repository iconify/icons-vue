<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="aw_cm5baq"/><path class="m53uwkh6x"/><path class="vf9h4pbzj"/><path clip-rule="evenodd" class="hfngqwbrl"/><path class="pm7t2gb8l"/><path class="phda8cbsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:printer" /></template>
<style>
.aw_cm5baq {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M5 7V3c0-.552.373-1 .833-1h8.334c.46 0 .833.448.833 1v4");
}

.ft5dv1b6b {
  fill: none;
}

.hfngqwbrl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M5 12v4.8c0 .663.373 1.2.833 1.2h8.334c.46 0 .833-.537.833-1.2V12");
}

.m53uwkh6x {
  fill: currentColor;
  d: path("M6 3v4a1 1 0 0 1-2 0V3c0-1.068.776-2 1.833-2h8.334C15.224 1 16 1.932 16 3v4a1 1 0 1 1-2 0V3z");
}

.phda8cbsc {
  fill: currentColor;
  d: path("M7 16a.5.5 0 0 1 0-1h6a.5.5 0 0 1 0 1zm0-2a.5.5 0 0 1 0-1h6a.5.5 0 0 1 0 1z");
}

.pm7t2gb8l {
  fill: currentColor;
  d: path("M6 16.8V12a1 1 0 1 0-2 0v4.8c0 1.154.727 2.2 1.833 2.2h8.334C15.273 19 16 17.954 16 16.8V12a1 1 0 1 0-2 0v4.8a.7.7 0 0 1-.029.2H6.029A.7.7 0 0 1 6 16.8");
}

.vf9h4pbzj {
  fill: currentColor;
  d: path("M4 6h12a3 3 0 0 1 3 3v5a3 3 0 0 1-3 3H4a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3");
}

</style>
