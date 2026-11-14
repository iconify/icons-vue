<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u-dbbte2p"/><path class="umw3mubll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shower-running" /></template>
<style>
.u-dbbte2p {
  d: path("M3.5 3H9a3 3 0 0 1 3 3v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.umw3mubll {
  d: path("M6.5 12a5.5 5.5 0 0 1 11 0Zm2 3l-.75 5M12 15v6m3.5-6l.75 5");
}

</style>
