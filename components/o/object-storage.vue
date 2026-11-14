<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="urirpovri"/><path class="k4iidbcyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:object-storage" /></template>
<style>
.k4iidbcyq {
  d: path("M8 7h4v4H8Zm4 0h4v4h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.urirpovri {
  d: path("M3.5 11h17l-2 10.5h-13Zm0 0a8.5 8.5 0 0 1 17 0");
}

</style>
