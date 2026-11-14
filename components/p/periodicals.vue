<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qeb8j6bgh"/><path class="ky780r74p"/><path class="b3ciglh9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:periodicals" /></template>
<style>
.b3ciglh9x {
  d: path("M11.75 11.5h5.5V18h-5.5Z");
}

.ky780r74p {
  d: path("M9 5h11v16.5H9Zm2.75 3.5h5.5");
}

.qeb8j6bgh {
  d: path("m8.75 21.5l-4-16l10.5-2.75l.5 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
