<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeprmzbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stretcher-sport" /></template>
<style>
.xeprmzbbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15h19m-18-2.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm7.75 2.5v-1.5a2.5 2.5 0 0 1 2.5-2.5h2.75a2 2 0 0 1 2 2v2m-13 0v3.5m13-3.5v3.5M12 3.5V8M9.75 5.75h4.5");
}

</style>
