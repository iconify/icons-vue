<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zu955kafx"/><path class="yu_vbv9kt"/><path class="j_efvl6tx"/><path class="zs843lqwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:octagon-alert-sharp-two-tone" /></template>
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

.yu_vbv9kt {
  d: path("M3 8.4L3 15.6L8.4 21L15.6 21L21 15.6L21 8.4L15.6 3L8.4 3L3 8.4Z");
}

.zs843lqwx {
  fill: currentColor;
  d: path("M13 16C13 16.5523 12.5523 17 12 17C11.4477 17 11 16.5523 11 16C11 15.4477 11.4477 15 12 15C12.5523 15 13 15.4477 13 16Z");
  stroke: none;
}

.zu955kafx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8.4C2 8.1348 2.1054 7.8804 2.2929 7.6929L7.6929 2.2929C7.8804 2.1054 8.1348 2 8.4 2L15.6 2C15.8652 2 16.1196 2.1054 16.3071 2.2929L21.7071 7.6929C21.8946 7.8804 22 8.1348 22 8.4L22 15.6C22 15.8652 21.8946 16.1196 21.7071 16.3071L16.3071 21.7071C16.1196 21.8946 15.8652 22 15.6 22L8.4 22C8.1348 22 7.8804 21.8946 7.6929 21.7071L2.2929 16.3071C2.1054 16.1196 2 15.8652 2 15.6L2 8.4Z");
  stroke: none;
}

</style>
