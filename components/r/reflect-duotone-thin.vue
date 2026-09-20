<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6n49udox"/><path class="lnt75bkgi"/><path class="q6gd3twiv"/><path class="h2-2dgnfu"/><path class="hzsvawc8s"/><path class="u8aszkb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reflect-duotone-thin" /></template>
<style>
.g6n49udox {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2-2dgnfu {
  d: path("M12 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hzsvawc8s {
  d: path("m8 8 -4 4 4 4");
}

.lnt75bkgi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q6gd3twiv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 8 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u8aszkb6i {
  d: path("m16 8 4 4 -4 4");
}

</style>
