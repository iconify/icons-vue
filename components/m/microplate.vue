<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jaaw_qdwq"/><path class="fj_wwx1rp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:microplate" /></template>
<style>
.fj_wwx1rp {
  d: path("M5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M16 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M5 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.jaaw_qdwq {
  d: path("M5.5 4.5h14a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2v-10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
