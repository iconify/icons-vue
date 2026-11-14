<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b2g11-mpz"/><path class="gevrtubnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-tank" /></template>
<style>
.b2g11-mpz {
  d: path("M4.5 4.5a7.5 2 0 1 0 15 0a7.5 2 0 1 0-15 0Z");
}

.gevrtubnm {
  d: path("M4.5 4.5v7a7.5 2 0 0 0 15 0v-7m-13 8.75L5 21.5m12.5-8.25L19 21.5m-16.5 0h19m-15.75-4h12.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
