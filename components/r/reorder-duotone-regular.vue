<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uq6n7rbdt"/><path class="axa755czi"/><path class="fco1n9k6o"/><path class="pd-i35blz"/><path class="tpiz71w3j"/><path class="zf-oqdytu"/><path class="sxy07wbdf"/><path class="eu9kkgbdm"/><path class="x3jqftbaj"/><path class="r3faxubne"/><path class="weza57brb"/><path class="al6h6yb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reorder-duotone-regular" /></template>
<style>
.al6h6yb3y {
  d: path("m2 18 2 2 2 -2");
}

.axa755czi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eu9kkgbdm {
  d: path("M9 12h12");
}

.fco1n9k6o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.sxy07wbdf {
  d: path("M9 7h12");
}

.tpiz71w3j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 6 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uq6n7rbdt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.weza57brb {
  d: path("m2 6 2 -2 2 2");
}

.x3jqftbaj {
  d: path("M9 17h12");
}

.zf-oqdytu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 18 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
