<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gru5shbyw"/><path class="rc-lw2bxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:signal-2g" /></template>
<style>
.gru5shbyw {
  fill: currentColor;
  d: path("M3 15.5h2.5v5H3ZM8.25 12h2.5v8.5h-2.5Z");
}

.rc-lw2bxy {
  d: path("M13.5 8H16v12.5h-2.5Zm5.25-4.5h2.5v17h-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
