<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxcrf6ftd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-rain-sharp" /></template>
<style>
.wxcrf6ftd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 13V12C7.5 9.515 9.515 7.5 12 7.5C14.485 7.5 16.5 9.515 16.5 12V13M1 12H4.5M19.5 12H23M4.636 4.636L6.282 6.282M19.364 4.636L17.718 6.282M12 4.5V1M3 16H21M7.276 19.447L5.724 22.553M12.276 19.447L10.724 22.553M17.276 19.447L15.724 22.553");
}

</style>
