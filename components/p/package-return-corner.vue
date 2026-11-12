<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zynudn-hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-return-corner" /></template>
<style>
.zynudn-hr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8v10a2 2 0 0 0 2 2h2M4 8l1-2c.613-1.226 1.387-2 2-2h10c.613 0 1.387.774 2 2l1 2M4 8h16m1 5v2a2 2 0 0 1-2 2h-6m3-3l-3 3l3 3");
}

</style>
