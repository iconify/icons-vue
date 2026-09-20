<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dmd--6w5x"/><path class="uwzwgsbfl"/><path class="xeokt-sqw"/><path class="a3hptlb1e"/><path class="bonttq6md"/><path class="u5fp3_7hb"/><path class="six8rqb9w"/><path class="nu8u0dbfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-to-speech-duotone-bold" /></template>
<style>
.a3hptlb1e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 6.8a6 6 0 0 1 0 10.4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bonttq6md {
  d: path("M2 9h8");
}

.dmd--6w5x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nu8u0dbfs {
  d: path("M17 6.8a6 6 0 0 1 0 10.4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.six8rqb9w {
  d: path("M15.5 9.4a3 3 0 0 1 0 5.2");
}

.u5fp3_7hb {
  d: path("M2 13h6");
}

.uwzwgsbfl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xeokt-sqw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.5 9.4a3 3 0 0 1 0 5.2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
