<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn-wl-y1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:silo" /></template>
<style>
.dn-wl-y1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 21V8a4 4 0 1 1 8 0v13m-9 0h18M12 8l6 3c1.226.613 2 1.387 2 2v8M4 13h8m-8 4h8");
}

</style>
