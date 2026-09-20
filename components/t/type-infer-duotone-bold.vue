<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rv-s8188y"/><path class="hwdq41llx"/><path class="qamt0gbak"/><path class="ivhcn-dzy"/><path class="i_kjavbri"/><path class="nilwl-6aj"/><path class="qtxvlht3c"/><path class="gl3o38_gx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:type-infer-duotone-bold" /></template>
<style>
.gl3o38_gx {
  d: path("M8 21h8");
}

.hwdq41llx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15.5 3 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i_kjavbri {
  d: path("m8.5 3 -5 5 5 5");
}

.ivhcn-dzy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 21h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nilwl-6aj {
  d: path("m15.5 3 5 5 -5 5");
}

.qamt0gbak {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qtxvlht3c {
  d: path("M8 17h8");
}

.rv-s8188y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8.5 3 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
