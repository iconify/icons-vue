<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hi7jtrwfv"/><path class="c8s6-ablk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-sharp-two-tone" /></template>
<style>
.c8s6-ablk {
  d: path("M16.5 12C16.5 14.4854 14.4854 16.5 12 16.5C9.5147 16.5 7.5 14.4854 7.5 12C7.5 9.5147 9.5147 7.5 12 7.5C14.4854 7.5 16.5 9.5147 16.5 12ZM19.5 12L23 12M17.3033 17.3033L19.7782 19.7782M12 19.5L12 23M6.6967 17.3033L4.2218 19.7782M4.5 12L1 12M6.6967 6.6967L4.2218 4.2218M12 4.5L12 1M17.3033 6.6967L19.7782 4.2218");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hi7jtrwfv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.5 12C17.5 14.8996 14.8996 17.5 12 17.5C9.1005 17.5 6.5 14.8996 6.5 12C6.5 9.1005 9.1005 6.5 12 6.5C14.8996 6.5 17.5 9.1005 17.5 12Z");
  stroke: none;
}

</style>
