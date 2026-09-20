<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="povg_rnmz"/><path class="vsaouab-m"/><path class="j9cys_e8h"/><path class="w68exsf2w"/><path class="vy55o7bfi"/><path class="j5_p9qdiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:storytime-duotone-regular" /></template>
<style>
.j5_p9qdiu {
  d: path("M13 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.j9cys_e8h {
  d: path("M12 12Q9 9 3 9v10q6 0 9 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.povg_rnmz {
  fill: currentColor;
  d: path("M5 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vsaouab-m {
  fill: currentColor;
  d: path("M13 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vy55o7bfi {
  d: path("M5 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.w68exsf2w {
  d: path("M12 12q3 -3 9 -3v10q-6 0 -9 3");
}

</style>
