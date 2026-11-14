<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnj3e4btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tarp-diamond" /></template>
<style>
.jnj3e4btk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 5l7 7l-7 7l-7-7Zm0 7h.01M12 2.25h.01M21.75 12h.01M12 21.75h.01M2.25 12h.01");
}

</style>
