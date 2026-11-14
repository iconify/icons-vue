<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v303uac9y"/><path class="q-mtxk_-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tabs-vertical" /></template>
<style>
.q-mtxk_-g {
  d: path("M2.5 11.25h4v3.5h-4Zm0 6.25h4V21h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v303uac9y {
  d: path("M4.5 2.5h15a2 2 0 0 1 2 2V19a2 2 0 0 1-2 2h-8.25a2 2 0 0 1-2-2V8.5H4.5a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2Z");
}

</style>
