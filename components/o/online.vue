<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x_25ybdoh"/><path class="p8pksabrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:online" /></template>
<style>
.p8pksabrr {
  d: path("M12 2.5a4 9.5 0 0 0 0 19m0-19a4 9.5 0 0 1 4 9.5m-1.25 6l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x_25ybdoh {
  d: path("M12 21.5a9.5 9.5 0 1 1 9.5-9.5m-19 0h19");
}

</style>
