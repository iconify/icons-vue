<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fy_2idkse"/><path class="j5a1k_bcd"/><path class="jh6waltkl"/><path class="bh5bi6dfy"/><path class="i_kjavbri"/><path class="nilwl-6aj"/><path class="qtxvlht3c"/><path class="gl3o38_gx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:type-infer-duotone-thin" /></template>
<style>
.bh5bi6dfy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 21h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fy_2idkse {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8.5 3 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gl3o38_gx {
  d: path("M8 21h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_kjavbri {
  d: path("m8.5 3 -5 5 5 5");
}

.j5a1k_bcd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15.5 3 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jh6waltkl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nilwl-6aj {
  d: path("m15.5 3 5 5 -5 5");
}

.qtxvlht3c {
  d: path("M8 17h8");
}

</style>
