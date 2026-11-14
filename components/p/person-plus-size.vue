<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyk8u65mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-plus-size" /></template>
<style>
.gyk8u65mf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 4.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1 16.75V19c-6-1-6-9 3.5-9s9.5 8 3.5 9v2.5M12 17v4.5");
}

</style>
