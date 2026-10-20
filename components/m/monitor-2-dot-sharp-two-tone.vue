<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="p31uxcled"/><path class="xqes2bcew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-dot-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p31uxcled {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M23 12L23 17C23 17.5523 22.5523 18 22 18L2 18C1.4477 18 1 17.5523 1 17L1 3C1 2.4477 1.4477 2 2 2L13 2L13 12L23 12ZM23 6C23 8.2091 21.2091 10 19 10C16.7909 10 15 8.2091 15 6C15 3.7909 16.7909 2 19 2C21.2091 2 23 3.7909 23 6Z");
  stroke: none;
}

.xqes2bcew {
  d: path("M13 3L2 3L2 17L22 17L22 12M12 17L12 21M7 21L17 21M22 6C22 7.6569 20.6569 9 19 9C17.3431 9 16 7.6569 16 6C16 4.3431 17.3431 3 19 3C20.6569 3 22 4.3431 22 6Z");
}

</style>
