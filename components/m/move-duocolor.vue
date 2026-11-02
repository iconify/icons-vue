<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt5z-ac7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:move-duocolor" /></template>
<style>
.tt5z-ac7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 6l-3-3l-3 3m3-3v9m-3 6l3 3l3-3m-3 3v-9M6 9l-3 3l3 3m-3-3h9m6 3l3-3l-3-3m3 3h-9");
}

</style>
