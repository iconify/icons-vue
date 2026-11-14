<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g8ailobwd"/><path class="ccmgq7b4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:piste-expert" /></template>
<style>
.ccmgq7b4f {
  d: path("M12 11v10.5m-3 0h6");
}

.g8ailobwd {
  fill: currentColor;
  d: path("m2.5 8l4-4l4 4l-4 4Zm11 0l4-4l4 4l-4 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
