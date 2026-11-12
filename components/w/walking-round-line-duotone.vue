<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="p7aa-3nja"/><path class="tldq1_vqs"/><path class="kk6lmubmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:walking-round-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kk6lmubmz {
  stroke-linejoin: round;
  d: path("M11.5 10L11.1582 13.4177C11.0801 14.1992 11.041 14.5899 11.1464 14.9581C11.2517 15.3263 11.4916 15.6372 11.9713 16.259L16.4004 22M11.5 10C11.3387 10 11.1601 10.0058 10.9698 10.0161C8.66494 10.141 7 12.1918 7 14.5M11.5 10C12.0042 10 12.5649 10.0565 13.0872 10.1315C14.2886 10.3041 15.2324 11.1973 15.6163 12.3488C15.8373 13.0118 16.5077 13.4154 17.1969 13.3005L19 13");
}

.p7aa-3nja {
  cx: 12.5px;
  cy: 4.5px;
  r: 2.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tldq1_vqs {
  d: path("M7 22L7.50917 21.5927C8.79506 20.564 9.67705 19.1148 10 17.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
