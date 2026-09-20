<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u5isvhblp"/><path class="b6p_2zb8n"/><path class="jq9ne5r-h"/><path class="ja2un0boz"/><path class="tkuw28bsv"/><path class="vse4gp0tl"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:queue-duotone-regular" /></template>
<style>
.b6p_2zb8n {
  fill: currentColor;
  d: path("M2 12.5a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ja2un0boz {
  d: path("M2 5a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2");
}

.jq9ne5r-h {
  fill: currentColor;
  d: path("M2 20a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tkuw28bsv {
  d: path("M2 12.5a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2");
}

.u5isvhblp {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vse4gp0tl {
  d: path("M2 20a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2");
}

</style>
