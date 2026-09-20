<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="fglpwbblz"/><path class="sf2b5k_6y"/><path class="juoha-k0p"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="x3ookvx2e"/><path class="kuui-zbsa"/><path class="c08_j9b_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:staleness-marker-duotone-bold" /></template>
<style>
.c08_j9b_a {
  d: path("m19.5 11.5 -3 3");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fglpwbblz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 17 4 -4h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.juoha-k0p {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19.5 11.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kuui-zbsa {
  d: path("m16.5 11.5 3 3");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sf2b5k_6y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16.5 11.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x3ookvx2e {
  d: path("m7 17 4 -4h3");
}

</style>
