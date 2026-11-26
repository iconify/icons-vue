<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4p8wo2tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:subscript-sharp" /></template>
<style>
.w4p8wo2tm {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.7704 3.6375L12 16L12.2999 16.3625M12.2998 3.6402L12 4L2 16L1.7681 16.2783M16.4323 15.3965L16.75 15.1L19 13L19 20M15 20L23 20");
}

</style>
