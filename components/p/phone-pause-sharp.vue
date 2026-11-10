<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us32v4oqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-pause-sharp" /></template>
<style>
.us32v4oqh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 1V9M22 1V9M2 4C2 2.9 2.895 2 4 2H9V8L7.739 8.95C7.487 9.13 7.339 9.43 7.339 9.75C7.339 9.9 7.374 10.05 7.442 10.19C8.805 12.96 11.045 15.19 13.812 16.56C13.95 16.63 14.101 16.66 14.254 16.66C14.569 16.66 14.865 16.51 15.054 16.26L16 15H22V20C22 21.1 21.105 22 20 22C10.059 22 2 13.94 2 4Z");
}

</style>
