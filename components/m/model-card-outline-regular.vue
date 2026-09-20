<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tkn_9lu9q"/><path class="qyilonb_g"/><path class="ae0h5kb0o"/><path class="lh672yb9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-card-outline-regular" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.lh672yb9q {
  d: path("M9 18h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qyilonb_g {
  d: path("M12 6.5 14.5 9 12 11.5 9.5 9Z");
}

.tkn_9lu9q {
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

</style>
