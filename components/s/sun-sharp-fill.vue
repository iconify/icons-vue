<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kwkaiub9l"/><path class="jvqu86ygv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jvqu86ygv {
  d: path("M19.5 12L23 12M17.3033 17.3033L19.7782 19.7782M12 19.5L12 23M6.6967 17.3033L4.2218 19.7782M4.5 12L1 12M6.6967 6.6967L4.2218 4.2218M12 4.5L12 1M17.3033 6.6967L19.7782 4.2218");
}

.kwkaiub9l {
  fill: currentColor;
  d: path("M17.5 12C17.5 14.8996 14.8996 17.5 12 17.5C9.1005 17.5 6.5 14.8996 6.5 12C6.5 9.1005 9.1005 6.5 12 6.5C14.8996 6.5 17.5 9.1005 17.5 12Z");
  stroke: none;
}

</style>
