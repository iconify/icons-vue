<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vyks9vbfn"/><path class="ngnirel9c"/><path class="p7w9wl2eu"/><path class="nwsr3kbjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scratchpad-outline-bold" /></template>
<style>
.ngnirel9c {
  d: path("M6 9h8");
}

.nwsr3kbjq {
  d: path("M6 17h6");
}

.p7w9wl2eu {
  d: path("M9 13h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
