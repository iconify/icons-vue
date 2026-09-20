<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="po7okpqgy"/><path class="au_o_7bss"/><path class="qir7x_1xu"/><path class="gk7zctbem"/><path class="q30q1h-zr"/><path class="dsax69fpp"/><path class="pek-tswzf"/><path class="dak2_9b1i"/><path class="hxoe7gx5p"/><path class="fyt8fyb5h"/><path class="x-egzxztr"/><path class="eg0ecwbhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:score-distribution-duotone-thin" /></template>
<style>
.au_o_7bss {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dak2_9b1i {
  d: path("M8 9v8");
}

.dsax69fpp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eg0ecwbhj {
  d: path("M3 19.5h18");
}

.fyt8fyb5h {
  d: path("M16 9v8");
}

.gk7zctbem {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 9v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxoe7gx5p {
  d: path("M12 5v12");
}

.pek-tswzf {
  d: path("M4 13v4");
}

.po7okpqgy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q30q1h-zr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qir7x_1xu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x-egzxztr {
  d: path("M20 13v4");
}

</style>
