<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="o_onwfy1m"/><path class="gyg0kccyn"/><path class="oomhv1bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-heart-rounded-broken" /></template>
<style>
.gyg0kccyn {
  stroke-linejoin: round;
  d: path("M16 9.69673C16 10.6812 17.1649 11.7213 18.0429 12.3656C18.4626 12.6736 18.6725 12.8276 19 12.8276C19.3275 12.8276 19.5374 12.6736 19.9571 12.3656C20.8352 11.7214 22 10.6812 22 9.69672C22 8.0235 20.35 7.39879 19 8.69135C17.65 7.39879 16 8.0235 16 9.69673Z");
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

</style>
