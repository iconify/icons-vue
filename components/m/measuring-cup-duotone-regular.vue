<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qge2u3g_r"/><path class="rp6dmcc7q"/><path class="m54fd64oa"/><path class="jt9xmstcg"/><path class="u-cg_ib1f"/><path class="dwqtbeylw"/><path class="zuuhu6bzg"/><path class="nreph_b_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:measuring-cup-duotone-regular" /></template>
<style>
.dwqtbeylw {
  d: path("M6 11h6");
}

.jt9xmstcg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 9a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m54fd64oa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nreph_b_j {
  d: path("M17 9a3 3 0 0 1 0 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qge2u3g_r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 6v13h12V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rp6dmcc7q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u-cg_ib1f {
  d: path("M5 6v13h12V6");
}

.zuuhu6bzg {
  d: path("M6 15h6");
}

</style>
