<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yn64c1dsb"/><path class="mi19z7sun"/><path class="tkn_9lu9q"/><path class="qyilonb_g"/><path class="ae0h5kb0o"/><path class="lh672yb9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-card-duotone-thin" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lh672yb9q {
  d: path("M9 18h4");
}

.mi19z7sun {
  fill: currentColor;
  d: path("M12 6.5 14.5 9 12 11.5 9.5 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qyilonb_g {
  d: path("M12 6.5 14.5 9 12 11.5 9.5 9Z");
}

.tkn_9lu9q {
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.yn64c1dsb {
  fill: currentColor;
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
