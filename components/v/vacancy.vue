<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f4j5zvbjz"/><path class="aqk7-vb8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vacancy" /></template>
<style>
.aqk7-vb8o {
  d: path("M9 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 3v9m0-4h2.5M12 21h2.5");
}

.f4j5zvbjz {
  d: path("M6 3h12m-6 0v3.5a1.25 1.25 0 0 1-2.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
