<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fr3h-pjps"/><path class="elr0ptbpx"/><path class="acyy74bpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:window-shutters" /></template>
<style>
.acyy74bpz {
  d: path("M14.75 3v17.5M8.5 11.75H21M6.5 6.5h2M6.5 17h2");
}

.elr0ptbpx {
  fill: currentColor;
  d: path("M2.5 3h4v17.5h-4Z");
}

.fr3h-pjps {
  d: path("M8.5 3H21v17.5H8.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
