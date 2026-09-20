<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h5m00ybuy"/><path class="ap_bu5bso"/><path class="z5anc_e2t"/><path class="xj9o_6b5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sync-two-way-outline-bold" /></template>
<style>
.ap_bu5bso {
  d: path("m15 6 3 3 -3 3");
}

.h5m00ybuy {
  d: path("M4 9h14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xj9o_6b5o {
  d: path("m9 12 -3 3 3 3");
}

.z5anc_e2t {
  d: path("M6 15h14");
}

</style>
