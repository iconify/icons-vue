<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zclnvzbpy"/><path class="ozdjujb5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radio-jingle" /></template>
<style>
.ozdjujb5g {
  d: path("M9.5 17.5v-12l9.5-2v12M9.5 9L19 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zclnvzbpy {
  d: path("M4.5 17.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm9.5-2a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
