<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="navc76bal"/><path class="gnn1wob3e"/><path class="umugi_b9i"/><path class="fmlaifbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:switch-case-outline-bold" /></template>
<style>
.fmlaifbpn {
  d: path("M12 16v4");
}

.gnn1wob3e {
  d: path("M18 10h3");
}

.navc76bal {
  d: path("m12 4 6 6 -6 6 -6 -6Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.umugi_b9i {
  d: path("M3 10h3");
}

</style>
