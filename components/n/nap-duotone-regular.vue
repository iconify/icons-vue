<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="cjx7a2bdd"/><path class="ibcxad5-k"/><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="odutg_b9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nap-duotone-regular" /></template>
<style>
.cjx7a2bdd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ibcxad5-k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 7c0 12 16 12 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.odutg_b9y {
  d: path("M4 7c0 12 16 12 16 0");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.ws1d0fbts {
  d: path("M20 4v16");
}

</style>
