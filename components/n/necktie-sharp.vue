<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph26gdc3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:necktie-sharp" /></template>
<style>
.ph26gdc3v {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.5 6.5L15 2L9 2L10.5 6.5M13.5 6.5L15.9996 16.9844L12 21.9999L8.0004 16.9844L10.5 6.5M13.5 6.5L10.5 6.5");
}

</style>
