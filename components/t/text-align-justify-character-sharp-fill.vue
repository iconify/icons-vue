<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nye9nrblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-align-justify-character-sharp-fill" /></template>
<style>
.nye9nrblr {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.87 10.23L7 3L11.13 10.23M9.285 7H4.715M14 3H22M14 9H22M2 15H22M2 21H22");
}

</style>
