<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mz5kvibtp"/><path class="vxy4ztabh"/><path class="w5i79a2na"/><path class="t8olluqaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:office-chair-outline-bold" /></template>
<style>
.mz5kvibtp {
  d: path("M6 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t8olluqaw {
  d: path("m7 21 3 -3h4l3 3");
}

.vxy4ztabh {
  d: path("M4 14h16");
}

.w5i79a2na {
  d: path("M12 14v4");
}

</style>
