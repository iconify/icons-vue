<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ys39w4b7n"/><path class="q-xlmac1a"/><circle class="zopjch_2q"/><path class="itzdzgb-y"/><path class="k97ygbbpb"/><path class="do-vovbeq"/><path class="gqsddbcer"/><path class="p7fs_qxcd"/><path class="vtj68-i3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-path-linear" /></template>
<style>
.do-vovbeq {
  d: path("M13 5L19 5");
}

.gqsddbcer {
  d: path("M13 11L19 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itzdzgb-y {
  d: path("M5 14H19C20.6569 14 22 12.6569 22 11C22 9.34315 20.6569 8 19 8H5C3.34315 8 2 9.34315 2 11C2 12.6569 3.34315 14 5 14Z");
}

.k97ygbbpb {
  d: path("M5 8H19C20.6569 8 22 6.65685 22 5C22 3.34315 20.6569 2 19 2H5C3.34315 2 2 3.34315 2 5C2 6.65685 3.34315 8 5 8Z");
}

.p7fs_qxcd {
  stroke-linejoin: round;
  d: path("M6 5H6.0001");
}

.q-xlmac1a {
  d: path("M12 17V14");
}

.vtj68-i3x {
  stroke-linejoin: round;
  d: path("M6 11H6.0001");
}

.ys39w4b7n {
  d: path("M22 19H14M10 19H2");
}

.zopjch_2q {
  cx: 12px;
  cy: 19px;
  r: 2px;
}

</style>
