<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzqk7fm3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-type-sharp" /></template>
<style>
.hzqk7fm3x {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 3L21 21L3 21ZM7 10L7 9L7 7L17 7L17 9L17 10M12 7L12 17M8.5 17L9.5 17L14.5 17L15.5 17");
}

</style>
