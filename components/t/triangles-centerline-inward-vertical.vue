<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdzk36bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangles-centerline-inward-vertical" /></template>
<style>
.fdzk36bhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2V22M7.8707 12.26L2.392 15.96C2.2183 16.08 2 15.93 2 15.7V8.3C2 8.07 2.2183 7.92 2.392 8.04L7.8707 11.74C8.0431 11.86 8.0431 12.14 7.8707 12.26ZM16.1293 12.26L21.608 15.96C21.7818 16.08 22 15.93 22 15.7V8.3C22 8.07 21.7818 7.92 21.608 8.04L16.1293 11.74C15.9569 11.86 15.9569 12.14 16.1293 12.26Z");
}

</style>
