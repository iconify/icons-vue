<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0itepj9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:play-off-sharp" /></template>
<style>
.e0itepj9g {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.4 14.4L6 20L6 6M15.1308 10.0872L18 12L16.7605 12.8263M1.7071 1.7071L22.2929 22.2929");
}

</style>
