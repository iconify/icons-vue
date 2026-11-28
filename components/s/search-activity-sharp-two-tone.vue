<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lp5posvtk"/><path class="tms_tccgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-activity-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lp5posvtk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.657 15.657C14.21 17.104 12.209 18 10 18C5.582 18 2 14.418 2 10C2 5.582 5.582 2 10 2C14.418 2 18 5.582 18 10C18 12.209 17.104 14.21 15.657 15.657Z");
  stroke: none;
}

.tms_tccgu {
  d: path("M17 10C17 11.933 16.217 13.683 14.95 14.95M17 10C17 6.134 13.866 3 10 3C6.134 3 3 6.134 3 10M17 10H12.5L11 12.5L9 7.5L7.5 10H3M14.95 14.95C13.683 16.217 11.933 17 10 17C6.134 17 3 13.866 3 10M14.95 14.95L14.293 14.293M14.95 14.95L21.293 21.293");
}

</style>
