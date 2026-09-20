<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="buk14h7lm"/><path class="axbworwuk"/><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="odutg_b9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nap-duotone-bold" /></template>
<style>
.axbworwuk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7c0 12 16 12 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.buk14h7lm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.odutg_b9y {
  d: path("M4 7c0 12 16 12 16 0");
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ws1d0fbts {
  d: path("M20 4v16");
}

</style>
