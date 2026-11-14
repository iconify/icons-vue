<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fqo_q6b-n"/><path class="i_-qqhb_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:self-guided-tour" /></template>
<style>
.fqo_q6b-n {
  d: path("M5.5 2.5h13v19h-13Zm5 2.5h3m-3 14h3");
}

.i_-qqhb_z {
  d: path("M10.25 9.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM12 11v5m0-2.25h1.75M12 16h1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
