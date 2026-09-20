<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q79rci8nx"/><path class="p-ctcpuri"/><path class="hp-ddcbtb"/><path class="uzrr--bsw"/><path class="pldoi_k0z"/><path class="s-mi-tbrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:span-tool-duotone-regular" /></template>
<style>
.hp-ddcbtb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 17h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-ctcpuri {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pldoi_k0z {
  d: path("M7 11h11");
}

.q79rci8nx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s-mi-tbrv {
  d: path("M10 17h11");
}

.uzrr--bsw {
  d: path("M3 5h9");
}

</style>
