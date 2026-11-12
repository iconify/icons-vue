<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t1afujhin"/><path class="t7jkg_bmt"/><path class="vny47hble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:repeat-one-linear" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t1afujhin {
  d: path("M9.5 19H9.00028C5.13428 19 2 15.866 2 12C2 8.13401 5.13401 5 9 5H11L9 3");
}

.t7jkg_bmt {
  d: path("M15 21L13 19H15C18.866 19 22 15.866 22 12C22 8.13401 18.866 5 15 5H14.5");
}

.vny47hble {
  d: path("M10.5 11.5L12 10V14");
}

</style>
