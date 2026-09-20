<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t69363l7x"/><path class="q_br9pbky"/><path class="ptaeireto"/><path class="e8vupfb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pill-bottle-outline-regular" /></template>
<style>
.e8vupfb9c {
  d: path("M9.5 14h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ptaeireto {
  d: path("M12 11.5v5");
}

.q_br9pbky {
  d: path("M8 8V4h8v4");
}

.t69363l7x {
  d: path("M6 8v13h12V8Z");
}

</style>
