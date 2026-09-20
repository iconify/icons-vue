<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oayt7ibmd"/><path class="rsllxf47k"/><path class="cmdo5slre"/><path class="dh-nlhghu"/><path class="ji4n7mbrt"/><path class="q7fssjt_q"/><path class="sxy07wbdf"/><path class="eu9kkgbdm"/><path class="x3jqftbaj"/><path class="r3faxubne"/><path class="weza57brb"/><path class="al6h6yb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reorder-duotone-bold" /></template>
<style>
.al6h6yb3y {
  d: path("m2 18 2 2 2 -2");
}

.cmdo5slre {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eu9kkgbdm {
  d: path("M9 12h12");
}

.ji4n7mbrt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 6 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oayt7ibmd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q7fssjt_q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 18 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.rsllxf47k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sxy07wbdf {
  d: path("M9 7h12");
}

.weza57brb {
  d: path("m2 6 2 -2 2 2");
}

.x3jqftbaj {
  d: path("M9 17h12");
}

</style>
