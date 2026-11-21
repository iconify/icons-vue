<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-hckhe8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pipe-section" /></template>
<style>
.z-hckhe8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 2V10C20 15.5228 15.5228 20 10 20H2M13 2V10C13 11.6569 11.6569 13 10 13H2M6 22V11M22 6H11");
}

</style>
