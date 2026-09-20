<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="efnmt0b_s"/><path class="ey8kebcwj"/><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="idh0ojb3a"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="oe-98mb0w"/><path class="c8tpvpbrt"/><path class="igggo2bgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:slice-analysis-duotone-regular" /></template>
<style>
.c8tpvpbrt {
  d: path("M7 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.efnmt0b_s {
  fill: currentColor;
  d: path("M7 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ey8kebcwj {
  fill: currentColor;
  d: path("M15 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.idh0ojb3a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.igggo2bgi {
  d: path("M15 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oe-98mb0w {
  d: path("M12 6v12");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

</style>
