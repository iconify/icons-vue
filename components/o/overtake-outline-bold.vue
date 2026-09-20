<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hcn-wubvk"/><path class="toy0nxbdm"/><path class="ler50rfbf"/><path class="caiwqabfd"/><path class="qw9zcf0wd"/><path class="beunabbsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:overtake-outline-bold" /></template>
<style>
.beunabbsv {
  d: path("M12.5 6.5 15 4l2.5 2.5");
}

.caiwqabfd {
  d: path("M6.5 10.5 9 8l2.5 2.5");
}

.hcn-wubvk {
  d: path("M3 2v20");
}

.ler50rfbf {
  d: path("M9 8v12");
}

.qw9zcf0wd {
  d: path("M15 4v12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.toy0nxbdm {
  d: path("M21 2v20");
}

</style>
