<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="re8wedc-w"/><path class="o4d2wxbke"/><path class="zl6g0h25d"/><path class="jszbb1ext"/><path class="ujgggmb5i"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:snow-mountain-duotone-thin" /></template>
<style>
.cjsg0ab2y {
  d: path("M2 20h20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jszbb1ext {
  d: path("m2 18 8 -8 4 4 6 -6 2 2");
}

.o4d2wxbke {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 13 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.re8wedc-w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 18 8 -8 4 4 6 -6 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ujgggmb5i {
  d: path("m7 13 3 -3 3 3");
}

.zl6g0h25d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
