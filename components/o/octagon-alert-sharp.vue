<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="up15_y9jb"/><path class="j_efvl6tx"/><path class="zs843lqwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:octagon-alert-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j_efvl6tx {
  d: path("M12 7L12 13");
}

.up15_y9jb {
  d: path("M3 15.6L3 8.4L8.4 3L15.6 3L21 8.4L21 15.6L15.6 21L8.4 21L3 15.6Z");
}

.zs843lqwx {
  fill: currentColor;
  d: path("M13 16C13 16.5523 12.5523 17 12 17C11.4477 17 11 16.5523 11 16C11 15.4477 11.4477 15 12 15C12.5523 15 13 15.4477 13 16Z");
  stroke: none;
}

</style>
