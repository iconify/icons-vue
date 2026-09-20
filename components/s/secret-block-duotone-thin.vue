<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cnjf-ebwx"/><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="wbj0eleyk"/><path class="e4zuzu8qe"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="b6gnpqbjb"/><path class="nzb-j6sxx"/><path class="rnyye8dag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:secret-block-duotone-thin" /></template>
<style>
.b6gnpqbjb {
  d: path("M10 10.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.cnjf-ebwx {
  fill: currentColor;
  d: path("M10 10.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.e4zuzu8qe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 13.5h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eh---ab1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.nzb-j6sxx {
  d: path("M12 12.5V15");
}

.r1p5_ebae {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rnyye8dag {
  d: path("M12 13.5h2.5");
}

.wbj0eleyk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12.5V15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
