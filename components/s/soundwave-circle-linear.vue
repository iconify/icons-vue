<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j-heh34pv"/><path class="cz-6xlbfk"/><path class="dvt7o1bcw"/><path class="w3r9-bcte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:soundwave-circle-linear" /></template>
<style>
.cz-6xlbfk {
  d: path("M17 10L17 14");
}

.dvt7o1bcw {
  d: path("M7 9L7 15");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-heh34pv {
  d: path("M12 7L12 17");
}

.w3r9-bcte {
  d: path("M12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22Z");
}

</style>
