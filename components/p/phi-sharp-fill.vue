<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h12o89jtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phi-sharp-fill" /></template>
<style>
.h12o89jtc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.4416 4.9724L6.9117 5.8205C6.3159 6.774 6 7.8757 6 9C6 12.3137 8.6863 15 12 15C15.3137 15 18 12.3137 18 9C18 5.6863 15.3137 3 12 3L12 22");
}

</style>
