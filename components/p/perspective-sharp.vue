<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkr037eed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:perspective-sharp" /></template>
<style>
.vkr037eed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 5.5H17l.47 1.43l3.31 10.14l.47 1.43H2.75l.47-1.43L6.53 6.93L7 5.5zm1.83 0l-1.41 13m4.75-13l1.41 13");
}

</style>
