<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jg_a1sh_j"/><path class="iisi-2xbw"/><path class="stlr8gbwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:self-service-bi" /></template>
<style>
.iisi-2xbw {
  fill: currentColor;
  d: path("M6.5 12h3v8.5h-3ZM11 3.5h3v8h-3Z");
}

.jg_a1sh_j {
  d: path("M3.5 3v17.5h9.1");
}

.stlr8gbwr {
  d: path("M11 18.5v2m5-1.75v-3.5a.75.75 0 0 1 1.5 0V18a.75.75 0 0 1 1.25 0A.75.75 0 0 1 20 18a.75.75 0 0 1 1.25.5v1.25c0 1.25-.75 2-2 2h-1c-.75 0-1.25-.25-1.75-1l-1.75-2a.75.75 0 0 1 1.25 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
