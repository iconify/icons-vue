<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di3orsbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-message-sharp" /></template>
<style>
.di3orsbap {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 4C10.6569 4 12 5.3431 12 7C12 8.6569 10.6569 10 9 10C7.3432 10 6 8.6569 6 7C6 5.3431 7.3432 4 9 4ZM11 21L2 21L2 20C2 16.6863 4.6863 14 8 14L10 14C10.2868 14 10.5733 14.0206 10.8571 14.0615M14 13L22 13L22 18L20 18L18 20.5L18 18L14 18Z");
}

</style>
