<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hm52d9bxd"/><path class="vamrmexbl"/><path class="e77gki8ci"/><path class="jdqylbbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:warehouse-pick-duotone-bold" /></template>
<style>
.e77gki8ci {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

.hm52d9bxd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20V10l3 -3h14l3 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jdqylbbkf {
  d: path("m9 14 2 2 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vamrmexbl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 14 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
