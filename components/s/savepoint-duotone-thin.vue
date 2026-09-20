<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z1ra8bb5p"/><path class="fa8lp8ket"/><path class="ukyojkvtr"/><path class="stexy9brj"/><path class="to02llleg"/><path class="jroakeb3a"/><path class="iup9trbmr"/><path class="u7m7z6ojw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:savepoint-duotone-thin" /></template>
<style>
.fa8lp8ket {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 4H3v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iup9trbmr {
  d: path("M12 6v4");
}

.jroakeb3a {
  d: path("M17 4h4v16h-4");
}

.stexy9brj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.to02llleg {
  d: path("M7 4H3v16h4");
}

.u7m7z6ojw {
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ukyojkvtr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z1ra8bb5p {
  fill: currentColor;
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
