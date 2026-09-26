<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd4b86b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vision-pro-sharp" /></template>
<style>
.qd4b86b0z {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7L17 7C19.7614 7 22 9.2386 22 12C22 14.7614 19.7614 17 17 17L15.39 17L13.61 14.3166L10.39 14.3166L8.61 17L7 17C4.2386 17 2 14.7614 2 12C2 9.2386 4.2386 7 7 7Z");
}

</style>
