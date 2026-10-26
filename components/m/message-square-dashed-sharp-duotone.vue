<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxcjn44mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-dashed-sharp-duotone" /></template>
<style>
.gxcjn44mc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8.75L3 3L7 3M9.5 3L14.5 3M17 3L21 3L21 8.75M21 11.25L21 17L17 17M15 17L10 17M8 17L7 17L3 21L3 11.25");
}

</style>
