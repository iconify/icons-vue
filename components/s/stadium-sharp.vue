<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u65lzsd7g"/><path class="xboyprb7n"/><path class="lntokpkxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stadium-sharp" /></template>
<style>
.lntokpkxj {
  d: path("M6.75 9.5a5.25 2 0 0 1 10.5 0a5.25 2 0 0 1-10.5 0Z");
}

.u65lzsd7g {
  d: path("M2.75 9.5a9.25 4.75 0 0 1 18.5 0v6a9.25 4.75 0 0 1-18.5 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xboyprb7n {
  d: path("M2.75 9.5a9.25 4.75 0 0 0 18.5 0M12 15.75v3M7 15v3m10-3v3");
}

</style>
