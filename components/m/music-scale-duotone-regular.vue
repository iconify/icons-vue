<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jz9jnbbik"/><path class="zjx9qrbec"/><path class="rmcdk3s9f"/><path class="psdg60bjt"/><path class="f7l3nxmbe"/><path class="xk6pmibqj"/><path class="aeyekmbly"/><path class="gnggw0bkv"/><path class="w3qv73i9r"/><path class="m7i92hb6f"/><path class="ve_htnadp"/><path class="b6rnmzrfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:music-scale-duotone-regular" /></template>
<style>
.aeyekmbly {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.b6rnmzrfq {
  d: path("M19 11V5");
}

.f7l3nxmbe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 15V9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gnggw0bkv {
  d: path("M7 19v-6");
}

.jz9jnbbik {
  fill: currentColor;
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m7i92hb6f {
  d: path("M13 15V9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.psdg60bjt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 19v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rmcdk3s9f {
  fill: currentColor;
  d: path("M15 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ve_htnadp {
  d: path("M15 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.w3qv73i9r {
  d: path("M9 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xk6pmibqj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 11V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zjx9qrbec {
  fill: currentColor;
  d: path("M9 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
