<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ufv0brdex"/><path class="pqdmd0bwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shadow-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pqdmd0bwf {
  d: path("M16 16L19.0727 19.0727M18 13L21.1151 16.1151M13 18L16.1148 21.1148M19 9L22.0019 12.0019M9 19L12.0014 22.0014");
}

.ufv0brdex {
  d: path("M7 3.3378C8.4709 2.487 10.1786 2 12 2C17.5228 2 22 6.4772 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 10.1786 2.487 8.4709 3.3378 7");
}

</style>
