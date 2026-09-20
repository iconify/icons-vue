<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rpia7ss3x"/><path class="ttk4e4b0g"/><path class="vhf3_kexp"/><path class="of6j6rbkz"/><path class="o-_d8xbww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:presentation-duotone-bold" /></template>
<style>
.o-_d8xbww {
  d: path("m7 12 3 -3 3 3 4 -4");
}

.of6j6rbkz {
  d: path("m7 21 5 -5 5 5");
}

.rpia7ss3x {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ttk4e4b0g {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.vhf3_kexp {
  d: path("M12 16v5");
}

</style>
