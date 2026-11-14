<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="utg1klbkn"/><path class="zrheyv1we"/><path class="t6-6gei8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-pin-dot" /></template>
<style>
.t6-6gei8o {
  fill: currentColor;
  d: path("M11 21a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.utg1klbkn {
  d: path("M12 17c-2.5-2.25-6.5-4.5-6.5-8a6.5 6.5 0 0 1 13 0c0 3.5-4 5.75-6.5 8Z");
}

.zrheyv1we {
  d: path("M9.5 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
