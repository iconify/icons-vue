<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l4a5a5bci"/><path class="vtfm0dbjp"/><path class="t87ohzbeq"/><path class="s7eyaw7qq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pause-duotone-bold" /></template>
<style>
.l4a5a5bci {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s7eyaw7qq {
  d: path("M15 4v16");
}

.t87ohzbeq {
  d: path("M9 4v16");
}

.vtfm0dbjp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
