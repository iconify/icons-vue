<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skyb54b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-dashed-sharp" /></template>
<style>
.skyb54b-n {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 15L3 21L21 21L21 15L3 15ZM7 3L3 3L3 7M21 7L21 3L17 3M3 9L3 12M21 9L21 12M9.5 3L14.5 3");
}

</style>
