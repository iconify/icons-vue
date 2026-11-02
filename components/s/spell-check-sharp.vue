<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm-kqz9jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:spell-check-sharp" /></template>
<style>
.vm-kqz9jy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9a3 3 0 1 0 6 0a3 3 0 0 0-6 0m6-3v6m4-8v8m0-3a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-1 8l3 3l6-6");
}

</style>
