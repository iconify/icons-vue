<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to0c2ub7t"><path class="p6xm5x-rc"/><path class="upr2r56ap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:terminal-asterisk-duotone" /></template>
<style>
.p6xm5x-rc {
  d: path("M8 5L8 15M4 13L12 7M4 7L12 13");
}

.to0c2ub7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.upr2r56ap {
  stroke-opacity: 0.4;
  d: path("M20 19L13 19");
}

</style>
