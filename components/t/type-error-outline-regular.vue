<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p1h-ezbbv"/><path class="hgui8bcaa"/><path class="lhfoj2bfk"/><path class="olup7y72x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:type-error-outline-regular" /></template>
<style>
.hgui8bcaa {
  d: path("m17 7 2.5 2.5L17 12");
}

.lhfoj2bfk {
  d: path("M12 6v4.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.olup7y72x {
  d: path("M11 13.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.p1h-ezbbv {
  d: path("M7 7 4.5 9.5 7 12");
}

</style>
