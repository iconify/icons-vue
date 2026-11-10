<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbojf1h-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-insert-sharp" /></template>
<style>
.vbojf1h-d {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 3H22M14 9H22M2 15H22M2 21H22M8.312 2.73L11 5.25L8.284 7.8M11 5.25H3V10");
}

</style>
