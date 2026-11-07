<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyhuexbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:newspaper-round" /></template>
<style>
.wyhuexbrg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 8a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4m0 0v12m4-12h6m-6 4h6m-6 4h6");
}

</style>
