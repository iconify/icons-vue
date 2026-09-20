<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bj6lsygie"/><path class="kg85x_b0m"/><path class="iwx-s0nix"/><path class="jtrmczbpr"/><path class="n6amu-bmd"/><path class="n_hih6bwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stream-duotone-regular" /></template>
<style>
.bj6lsygie {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iwx-s0nix {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 18h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jtrmczbpr {
  d: path("M2 6h14");
}

.kg85x_b0m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n_hih6bwb {
  d: path("M2 18h14");
}

.n6amu-bmd {
  d: path("M8 12h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
