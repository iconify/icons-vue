<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="t8qt32blf"/><path class="sbzfdkqzv"/><path class="qcb83wbuk"/><path class="p28uk85oq"/><path class="k6nj2fbya"/><path class="d223d_x9q"/><path class="zrdou8b0n"/><path class="uxy9sxbfx"/><path class="wgmfnvzml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tokenizer-duotone-thin" /></template>
<style>
.ck7sgubpk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d223d_x9q {
  d: path("M3 12h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.p28uk85oq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 19h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qcb83wbuk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sbzfdkqzv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t8qt32blf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uxy9sxbfx {
  d: path("M3 19h10");
}

.wgmfnvzml {
  d: path("M16 19h5");
}

.zrdou8b0n {
  d: path("M12 12h9");
}

</style>
