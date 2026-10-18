<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqp9q5oqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parenthesis-left-sharp-two-tone" /></template>
<style>
.vqp9q5oqs {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.2858 1.6897L13.9902 2C11.4224 4.6962 9.9902 8.2767 9.9902 12C9.9902 15.7233 11.4224 19.3038 13.9902 22L14.2858 22.3103");
}

</style>
