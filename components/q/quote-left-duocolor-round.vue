<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf76-bcuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:quote-left-duocolor-round" /></template>
<style>
.zf76-bcuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11h3a3 3 0 1 1-3 3za4 4 0 0 1 4-4m6 4h3a3 3 0 1 1-3 3za4 4 0 0 1 4-4");
}

</style>
