<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4p5e-bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mammal" /></template>
<style>
.l4p5e-bye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c-3 0-6 3.5-6 6c0 2 1.5 3 3 3s2-.75 3-.75s1.5.75 3 .75s3-1 3-3c0-2.5-3-6-6-6Zm-9.75-1.5a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0ZM7 5a1.75 2.5 0 1 0 3.5 0A1.75 2.5 0 1 0 7 5Zm6.5 0A1.75 2.5 0 1 0 17 5a1.75 2.5 0 1 0-3.5 0Zm4.75 5.5a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0Z");
}

</style>
