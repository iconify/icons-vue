<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y8a66ib3e"/><path class="p4weyfsrl"/><path class="l9rn44bjs"/><path class="w0e70wbbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sandbag-outline-bold" /></template>
<style>
.l9rn44bjs {
  d: path("m10.5 8 3 3");
}

.p4weyfsrl {
  d: path("M16 13v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w0e70wbbt {
  d: path("M3 21.5h18");
}

.y8a66ib3e {
  d: path("M8 4v15");
}

</style>
