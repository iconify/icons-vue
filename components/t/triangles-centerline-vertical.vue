<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="las0ojb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangles-centerline-vertical" /></template>
<style>
.las0ojb1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2V22M2.1293 12.26L7.608 15.96C7.7818 16.08 8 15.93 8 15.7V8.3C8 8.07 7.7818 7.92 7.608 8.04L2.1293 11.74C1.9569 11.86 1.9569 12.14 2.1293 12.26ZM21.8707 12.26L16.392 15.96C16.2182 16.08 16 15.93 16 15.7V8.3C16 8.07 16.2182 7.92 16.392 8.04L21.8707 11.74C22.0431 11.86 22.0431 12.14 21.8707 12.26Z");
}

</style>
