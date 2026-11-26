<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tojw79abd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zodiac-libra-sharp" /></template>
<style>
.tojw79abd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1 13L6 13L6 11C6 7.6863 8.6863 5 12 5C15.3137 5 18 7.6863 18 11L18 13L23 13M1 19L23 19");
}

</style>
