<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zv2nn_bwf"/><path class="jwikj1bfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jwikj1bfu {
  d: path("m10.293 12.293l3-3a.999.999 0 1 1 1.414 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

.zv2nn_bwf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.684 5.051l6-2a2.582 2.582 0 0 1 3.265 3.265l-4 12c-.187.56-.612.986-1.178 1.159c-.476.145-.981.098-1.449-.058a3.7 3.7 0 0 1-1.25-.728a4 4 0 0 1-.966-1.242l-1-2a5.72 5.72 0 0 0-2.553-2.553l-2-1a4 4 0 0 1-1.242-.966a3.7 3.7 0 0 1-.728-1.25c-.156-.468-.203-.973-.058-1.449a1.78 1.78 0 0 1 1.159-1.178Z");
}

</style>
