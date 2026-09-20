<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iczafxbjt"/><path class="p2u6mt7uf"/><path class="gim3-nbjb"/><path class="h2-2dgnfu"/><path class="srofgib5x"/><path class="m7gli2e_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trunk-based-duotone-regular" /></template>
<style>
.gim3-nbjb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 12.5 12 17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2-2dgnfu {
  d: path("M12 3v18");
}

.iczafxbjt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m7gli2e_k {
  d: path("M16.5 12.5 12 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p2u6mt7uf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 6.5 12 11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.srofgib5x {
  d: path("M7.5 6.5 12 11");
}

</style>
