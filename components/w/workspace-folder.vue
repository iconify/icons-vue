<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ih1lrlw7a"/><path class="ll7bebbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:workspace-folder" /></template>
<style>
.ih1lrlw7a {
  d: path("M3 11a2 2 0 0 1 2-2h3.5l2 2H19a2 2 0 0 1 2 2v6.5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.ll7bebbps {
  d: path("m6 9l-.75-4.5l5-.75L11 11m3 0l.75-8l5 .75L19 11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
