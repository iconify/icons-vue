<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y72idacvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:row-plus-round" /></template>
<style>
.y72idacvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 7a3 3 0 0 1 3-3h10a3 3 0 0 1 0 6H7a3 3 0 0 1-3-3m5 10h6m-3-3v6");
}

</style>
