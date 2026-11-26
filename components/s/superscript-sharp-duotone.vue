<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bpnshvb6t"/><path class="lzb2rabzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:superscript-sharp-duotone" /></template>
<style>
.bpnshvb6t {
  stroke-opacity: 0.4;
  d: path("M1.7681 7.7217L2 8L12 20L12.2998 20.3598M12.2998 7.6402L12 8L1.7704 20.3625");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lzb2rabzn {
  d: path("M16.4323 6.3965L16.75 6.1L19 4L19 11M15 11L23 11");
}

</style>
