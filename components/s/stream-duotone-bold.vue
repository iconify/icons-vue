<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="udw1i4tmx"/><path class="vhfnkdb-k"/><path class="vvz16lq6z"/><path class="jtrmczbpr"/><path class="n6amu-bmd"/><path class="n_hih6bwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stream-duotone-bold" /></template>
<style>
.jtrmczbpr {
  d: path("M2 6h14");
}

.n_hih6bwb {
  d: path("M2 18h14");
}

.n6amu-bmd {
  d: path("M8 12h14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.udw1i4tmx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vhfnkdb-k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vvz16lq6z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
