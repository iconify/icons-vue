<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="twn7f-jfj"/><circle class="w9lhlfbwv"/><path class="yxh9dkjfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:redbus" /></template>
<style>
.twn7f-jfj {
  cx: 15.177px;
  cy: 32.525px;
  r: 4.134px;
}

.w9lhlfbwv {
  cx: 34.357px;
  cy: 31.028px;
  r: 4.134px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yxh9dkjfb {
  d: path("m19.077 31.154l11.201-1.213m7.776-.842l4.638-.46c1.964-6.99.273-15.487-4.248-16.68c-5.606-1.48-21.971-.303-30.963 3.532c-4.747 2.096-2.966 9.312-.557 16.979l4.024-.436");
}

</style>
