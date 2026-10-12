<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="s77rrwb7q"/><circle class="aehem7bjh"/><path class="guhbvob-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:screen-record-sharp" /></template>
<style>
.aehem7bjh {
  cx: 12px;
  cy: 10.25px;
  r: 2.75px;
}

.guhbvob-p {
  d: path("M12 16.75v3.5m-3.75 0h7.5");
}

.s77rrwb7q {
  d: path("M2.75 3.75h18.5v13H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
