<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaueidcrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:move-sharp-duotone" /></template>
<style>
.eaueidcrq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12L2 12M5.2929 15.2929L2 12L5.2929 8.7071M14 12L22 12M18.7071 8.7071L22 12L18.7071 15.2929M12 10L12 2M8.7071 5.2929L12 2L15.2929 5.2929M12 14L12 22M15.2929 18.7071L12 22L8.7071 18.7071");
}

</style>
