<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkkuh9ebd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:swiss-franc-sharp" /></template>
<style>
.vkkuh9ebd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 2L18 2L9 2L9 22L9 23M8 11L9 11L16 11L17 11M5 16L6 16L14 16L15 16");
}

</style>
