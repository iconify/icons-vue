<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xf1regb7a"/><path class="f3iw3wbzh"/><path class="w1z4wnfys"/><path class="kamdbib6v"/><path class="wlpqxdb6z"/><path class="uduptbc9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:table-scan-duotone-regular" /></template>
<style>
.f3iw3wbzh {
  fill: currentColor;
  d: path("M8 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kamdbib6v {
  d: path("M2 7h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uduptbc9i {
  d: path("m13 20 2 2");
}

.w1z4wnfys {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.wlpqxdb6z {
  d: path("M8 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.xf1regb7a {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
