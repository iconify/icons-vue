<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5ivy6b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:open-office" /></template>
<style>
.q5ivy6b5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3h8v18H8ZM2.75 4.75h2.5v3.5h-2.5Zm0 5.5h2.5v3.5h-2.5Zm0 5.5h2.5v3.5h-2.5Zm16-11h2.5v3.5h-2.5Zm0 5.5h2.5v3.5h-2.5Zm0 5.5h2.5v3.5h-2.5Z");
}

</style>
