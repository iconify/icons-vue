<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ratiiit7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tilde-duotone" /></template>
<style>
.ratiiit7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 13.8563C5.5395 11.8015 6.5934 10.4402 7.9162 10.0894C9.239 9.7386 10.7149 10.4291 12 12C13.2851 13.5709 14.761 14.2614 16.0838 13.9106C17.4066 13.5598 18.4605 12.1985 19 10.1437");
}

</style>
