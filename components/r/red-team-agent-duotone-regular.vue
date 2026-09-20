<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kosxb-loy"/><path class="ez43robbw"/><path class="skbifdbcx"/><path class="mj0gsdv6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:red-team-agent-duotone-regular" /></template>
<style>
.ez43robbw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 10 -4.5 4.5H16L11.5 19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kosxb-loy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mj0gsdv6h {
  d: path("m18 10 -4.5 4.5H16L11.5 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
