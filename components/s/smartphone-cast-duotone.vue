<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u2k281qqc"/><path class="j6-4mlbyu"/><path class="oj7ascbsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-cast-duotone" /></template>
<style>
.j6-4mlbyu {
  d: path("M4 18C6.2091 18 8 19.7909 8 22M4 14C8.4183 14 12 17.5817 12 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oj7ascbsc {
  fill: currentColor;
  d: path("M5 22C5 22.5523 4.5523 23 4 23C3.4477 23 3 22.5523 3 22C3 21.4477 3.4477 21 4 21C4.5523 21 5 21.4477 5 22Z");
  stroke: none;
}

.u2k281qqc {
  stroke-opacity: 0.4;
  d: path("M6 10.1678L6 6C6 3.7909 7.7909 2 10 2L16 2C18.2091 2 20 3.7909 20 6L20 18C20 20.2091 18.2091 22 16 22M11.5 6L14.5 6");
}

</style>
