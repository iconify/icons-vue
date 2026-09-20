<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nqda50bqs"/><path class="bg2ejdbaq"/><path class="urilmibxp"/><path class="x37ahcyum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spin-wheel-outline-bold" /></template>
<style>
.bg2ejdbaq {
  d: path("M12 5v16");
}

.nqda50bqs {
  d: path("M4 13a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.urilmibxp {
  d: path("M4 13h16");
}

.x37ahcyum {
  d: path("M9 2h6l-3 3Z");
}

</style>
