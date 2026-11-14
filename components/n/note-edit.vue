<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="upbcgobek"/><path class="nmt-o11bm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:note-edit" /></template>
<style>
.nmt-o11bm {
  d: path("M14 20v-4a2 2 0 0 1 2-2h4m-6.879-7.036l1.415 1.415l-4.597 4.596l-1.767.353l.353-1.767Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.upbcgobek {
  d: path("M4 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8l-6 6H6a2 2 0 0 1-2-2Z");
}

</style>
