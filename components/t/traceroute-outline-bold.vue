<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xq1pi7btv"/><path class="qi3wr9i3q"/><path class="q686vz2zk"/><path class="zky22zblb"/><path class="j4nym3cre"/><path class="m1z_l4h_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:traceroute-outline-bold" /></template>
<style>
.j4nym3cre {
  d: path("m6 16 2 -2");
}

.m1z_l4h_u {
  d: path("m12 11 2 -2");
}

.q686vz2zk {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qi3wr9i3q {
  d: path("M8 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xq1pi7btv {
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zky22zblb {
  d: path("M20 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
