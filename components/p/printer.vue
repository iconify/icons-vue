<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eb6lmwbwa"/><path class="ztz70bc9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:printer" /></template>
<style>
.eb6lmwbwa {
  d: path("M6.5 17h-2a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-2v-3h-11Zm0-9V4.5a1 1 0 0 1 1-1h9a1 1 0 0 1 1 1V8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ztz70bc9o {
  d: path("M6.5 14h11v6.5h-11ZM18 11h.01");
}

</style>
