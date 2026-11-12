<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="l_z2a8vzi"/><path class="qn-0a-fjj"/><path class="yewbpls5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-bug-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_z2a8vzi {
  cx: 11px;
  cy: 11px;
  r: 9px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qn-0a-fjj {
  d: path("M14 10V12C14 13.6569 12.6569 15 11 15M14 10C14 8.34315 12.6569 7 11 7C9.34315 7 8 8.34315 8 10M14 10H11M8 11V12C8 13.6569 9.34315 15 11 15M8 11V10M8 11H6.5M8 10H11M11 15V10M14.0715 11H15.5M14 13.5L15 14M8 13.5L7 14M14 8.5L15 8M8 8.5L7 8");
}

.yewbpls5v {
  d: path("M21.4094 21.4094C21.636 21.1828 21.7493 21.0695 21.812 20.9748C22.1793 20.4202 21.99 19.6699 21.4036 19.3559C21.3035 19.3023 21.15 19.2563 20.843 19.1643C20.5075 19.0638 20.3398 19.0136 20.2218 19.0038C19.5268 18.9466 18.9466 19.5268 19.0038 20.2218C19.0136 20.3398 19.0638 20.5076 19.1643 20.843C19.2563 21.15 19.3023 21.3035 19.3559 21.4036C19.6699 21.99 20.4202 22.1793 20.9748 21.812C21.0695 21.7493 21.1828 21.636 21.4094 21.4094Z");
}

</style>
