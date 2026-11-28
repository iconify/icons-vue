<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msqa_6g4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:redo-sharp-duotone" /></template>
<style>
.msqa_6g4y {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18.9998L3 17.9998C3 13.9534 5.3726 10.283 9.0622 8.6216C12.7518 6.9602 17.0727 7.6166 20.1025 10.2987L20.6054 10.7439M21 5.0002L21 11L15 11");
}

</style>
