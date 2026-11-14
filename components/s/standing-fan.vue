<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4sjzccur"/><path class="mfre3mace"/><path class="f8mnvqxfr"/><path class="yr926ac9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:standing-fan" /></template>
<style>
.d4sjzccur {
  d: path("M5.25 8.75a6.75 6.75 0 1 0 13.5 0a6.75 6.75 0 1 0-13.5 0ZM12 15.5v6m-4.5 0h9");
}

.f8mnvqxfr {
  d: path("m12.842 7.792l-1.25 2.166l-3.681-2.125l1.25-2.166Z");
}

.mfre3mace {
  d: path("M10.75 8.5h2.5v4.25h-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yr926ac9w {
  d: path("m12.408 9.958l-1.25-2.166l3.681-2.125l1.25 2.166Z");
}

</style>
