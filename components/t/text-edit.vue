<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9l6gnkex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-edit" /></template>
<style>
.y9l6gnkex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 15v-3l8-8a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 1 0 2l-8 8zm6-9l3 3M3 21l3-3l3 3m4 0h8");
}

</style>
