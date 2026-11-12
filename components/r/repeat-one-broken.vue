<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vny47hble"/><path class="brc86cc0s"/><path class="epa2j5v2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:repeat-one-broken" /></template>
<style>
.brc86cc0s {
  d: path("M9.5 19H9.00028C6.62153 19 4.51981 17.8135 3.25478 16M9 3L11 5H9C5.13401 5 2 8.13401 2 12");
}

.epa2j5v2j {
  d: path("M15 21L13 19H15C18.866 19 22 15.866 22 12M14.5 5H15C17.3787 5 19.4804 6.18652 20.7453 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vny47hble {
  d: path("M10.5 11.5L12 10V14");
}

</style>
