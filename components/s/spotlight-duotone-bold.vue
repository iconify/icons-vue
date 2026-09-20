<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oqmtbdmdz"/><path class="ubuqkjbja"/><path class="li5x4yeoz"/><path class="ed9actbwe"/><path class="xt7b-dbai"/><path class="kc8gmclyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spotlight-duotone-bold" /></template>
<style>
.ed9actbwe {
  d: path("M6 11.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.kc8gmclyk {
  d: path("M14 11.5h4");
}

.li5x4yeoz {
  d: path("M3 9a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.oqmtbdmdz {
  fill: currentColor;
  d: path("M3 9a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
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

.ubuqkjbja {
  fill: currentColor;
  d: path("M6 11.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xt7b-dbai {
  d: path("m9.5 13 2 2");
}

</style>
