<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="goiz_9b_e"/><path class="v5u2kyfgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thermostat-heat" /></template>
<style>
.goiz_9b_e {
  d: path("M6.551 19.782a9.5 9.5 0 1 1 10.898 0M12 2.5v2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5u2kyfgc {
  d: path("M12 8c0 2.5 4 3.5 4 6.5a4 4 0 0 1-8 0c0-2 1-3 2-3.5c0 1.5.75 2.25 1.5 2.25C11.5 11 11 9.5 12 8Z");
}

</style>
