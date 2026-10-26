<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gocvo6bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-dashed-duotone" /></template>
<style>
.gocvo6bhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7.75L3 6C3 4.3431 4.3431 3 6 3M10.5 3L13.5 3M18 3C19.6569 3 21 4.3431 21 6L21 7.75M21 12.25L21 14C21 15.6569 19.6569 17 18 17M14 17L11 17M7 17L3 21L3 12.25");
}

</style>
