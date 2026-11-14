<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tgx030-6f"/><path class="fozkzubxj"/><path class="bn06y9blz"/><path class="yv170_97h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:xray" /></template>
<style>
.bn06y9blz {
  d: path("M7.75 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.fozkzubxj {
  d: path("M6 9.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.tgx030-6f {
  d: path("M3 2.5h18v19H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yv170_97h {
  d: path("M15 14.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM9.5 9.5l5 5");
}

</style>
