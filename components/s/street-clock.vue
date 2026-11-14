<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f0eti4_5i"/><path class="jojse1b2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:street-clock" /></template>
<style>
.f0eti4_5i {
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm5 5V21m-3.5 0h7");
}

.jojse1b2w {
  d: path("M12 5.25V7.5h2M9.75 16h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
