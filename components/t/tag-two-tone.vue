<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f5ssbf2_o"/><path class="e5futabtb"/><path class="s1f4hpnzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-two-tone" /></template>
<style>
.e5futabtb {
  d: path("M2 5C2 3.343146 3.343146 2 5 2L11.171573 2C11.702006 2 12.210714 2.210714 12.585786 2.585786L21.414213 11.414213C22.195262 12.195262 22.195262 13.461592 21.414213 14.24264L14.24264 21.414213C13.461592 22.195262 12.195262 22.195262 11.414213 21.414213L2.585786 12.585786C2.210714 12.210714 2 11.702006 2 11.171573Z");
}

.f5ssbf2_o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 5C1 2.790861 2.790861 1 5 1L11.171573 1C11.967223 1 12.730285 1.316071 13.292894 1.87868L22.12132 10.707107C23.292893 11.87868 23.292893 13.778174 22.12132 14.949747L14.949747 22.12132C13.778174 23.292893 11.87868 23.292893 10.707107 22.12132L1.87868 13.292894C1.316071 12.730285 1 11.967223 1 11.171573Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s1f4hpnzw {
  fill: currentColor;
  d: path("M9.5 8C9.5 8.8284 8.8284 9.5 8 9.5C7.1716 9.5 6.5 8.8284 6.5 8C6.5 7.1716 7.1716 6.5 8 6.5C8.8284 6.5 9.5 7.1716 9.5 8Z");
  stroke: none;
}

</style>
