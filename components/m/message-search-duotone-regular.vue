<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sqmravmye"/><path class="mvybygobp"/><path class="hbdbg_bcy"/><path class="lyjarcbwz"/><path class="ztcfio00z"/><path class="i4ag71b-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:message-search-duotone-regular" /></template>
<style>
.hbdbg_bcy {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.i4ag71b-h {
  d: path("m13.5 12.5 2 2");
}

.lyjarcbwz {
  d: path("M7 18v3l3 -3");
}

.mvybygobp {
  fill: currentColor;
  d: path("M7.5 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sqmravmye {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ztcfio00z {
  d: path("M7.5 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

</style>
