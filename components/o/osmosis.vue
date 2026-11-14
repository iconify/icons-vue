<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="in6wolo3y"/><path class="d-3cqzb-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:osmosis" /></template>
<style>
.d-3cqzb-s {
  d: path("m15 12l2.5 2.5L15 17");
}

.in6wolo3y {
  d: path("M3.5 4v14a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2V4M12 4v16M3.5 10H12m0-3h8.5m-14 7.5h11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
