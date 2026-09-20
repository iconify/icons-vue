<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b5ak1dhxf"/><path class="kw50e_bvi"/><path class="k35wv8y0z"/><path class="eojr-cxjg"/><path class="sqpfjbblj"/><path class="h23_vdqvb"/><path class="dxxnlbcax"/><path class="a71lhwniq"/><path class="a-r3j5f7z"/><path class="xt7079b9x"/><path class="qvytntb8g"/><path class="s13ysjbyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ocr-duotone-regular" /></template>
<style>
.a-r3j5f7z {
  d: path("M3 16v4h5");
}

.a71lhwniq {
  d: path("M16 4h5v4");
}

.b5ak1dhxf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8V4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dxxnlbcax {
  d: path("M3 8V4h5");
}

.eojr-cxjg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 20h5v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h23_vdqvb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 14h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k35wv8y0z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16v4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kw50e_bvi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 4h5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qvytntb8g {
  d: path("M7 10h10");
}

.s13ysjbyf {
  d: path("M7 14h7");
}

.sqpfjbblj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 10h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xt7079b9x {
  d: path("M16 20h5v-4");
}

</style>
