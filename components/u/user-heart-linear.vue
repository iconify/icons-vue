<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="o_onwfy1m"/><path class="geogrv1gb"/><path class="cvfjvfbdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-heart-linear" /></template>
<style>
.cvfjvfbdt {
  stroke-linejoin: round;
  d: path("M18.0885 12.5385C17.2058 11.8648 16 11.1121 16 9.69973C16 8.28732 17.65 7.28567 19 8.64354C20.35 7.28567 22 8.28732 22 9.69973C22 11.1121 20.7942 11.8648 19.9115 12.5385C19.6 12.7762 19.3 13 19 13C18.7 13 18.4 12.7762 18.0885 12.5385Z");
}

.geogrv1gb {
  d: path("M18 17.5C18 19.9853 18 22 10 22C2 22 2 19.9853 2 17.5C2 15.0147 5.58172 13 10 13C14.4183 13 18 15.0147 18 17.5Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_onwfy1m {
  cx: 10px;
  cy: 6px;
  r: 4px;
}

</style>
