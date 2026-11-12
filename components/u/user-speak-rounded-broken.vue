<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="o_onwfy1m"/><path class="sfxgh6bez"/><path class="d8f9mr75j"/><path class="oomhv1bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-speak-rounded-broken" /></template>
<style>
.d8f9mr75j {
  d: path("M17 4C17 4 18 4.6 18 6C18 7.4 17 8 17 8");
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

.oomhv1bom {
  d: path("M13 20.6151C12.0907 20.8619 11.0736 21 10 21C6.13401 21 3 19.2091 3 17C3 14.7909 6.13401 13 10 13C13.866 13 17 14.7909 17 17C17 17.3453 16.9234 17.6804 16.7795 18");
}

.sfxgh6bez {
  d: path("M19 2C19 2 21 3.2 21 6C21 8.8 19 10 19 10");
}

</style>
