<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t-_rumbqm"/><circle class="mc1uouhee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tennis-ball-sharp" /></template>
<style>
.mc1uouhee {
  cx: 18.75px;
  cy: 18.75px;
  r: 2.25px;
}

.t-_rumbqm {
  d: path("M18.7 5.05a7 5.5-45 1 1-9.9 9.9a7 5.5-45 1 1 9.9-9.9Zm-9.02 6.54l5.66-5.66m-3.18 8.14l5.66-5.66M8.8 14.95l-4.55 4.8");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
