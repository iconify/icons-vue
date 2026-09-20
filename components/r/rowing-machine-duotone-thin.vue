<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uau0kschl"/><path class="ja7s-m1mr"/><path class="ti2-e6mha"/><path class="ex7acbbzc"/><path class="esx8xg2rn"/><path class="yngda3bvc"/><path class="x1_r36phd"/><path class="rrzohjbez"/><path class="gstzuxb9r"/><path class="wggowmhtc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rowing-machine-duotone-thin" /></template>
<style>
.esx8xg2rn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 9h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ex7acbbzc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gstzuxb9r {
  d: path("M5 7v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja7s-m1mr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rrzohjbez {
  d: path("M12 12v3");
}

.ti2-e6mha {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uau0kschl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 15h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wggowmhtc {
  d: path("M5 9h4");
}

.x1_r36phd {
  d: path("M9 12h6");
}

.yngda3bvc {
  d: path("M3 15h18");
}

</style>
