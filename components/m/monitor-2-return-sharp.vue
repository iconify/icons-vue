<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7311cbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-return-sharp" /></template>
<style>
.e7311cbrz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3L2 3L2 17L22 17L22 12M12 17L12 21M7 21L17 21M22 2L22 7L16 7M18.2929 4.7071L16 7L18.2929 9.2929");
}

</style>
