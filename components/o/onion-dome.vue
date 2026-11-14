<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kj8p9wbrg"/><path class="bsl4e65ev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:onion-dome" /></template>
<style>
.bsl4e65ev {
  d: path("M10.5 21.5V19a1.5 1.5 0 0 1 3 0v2.5");
}

.kj8p9wbrg {
  d: path("M10.5 11.5c-6.5-2-6-5.5 1.5-9c7.5 3.5 8 7 1.5 9Zm-2 0h7v3h-7Zm-3 3h13v7h-13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
