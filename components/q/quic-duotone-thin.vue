<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jm_ntdbid"/><path class="vhdygzbly"/><path class="eimg1ibhu"/><path class="sz5he4mqt"/><path class="a78831x8h"/><path class="lg40ofb3n"/><path class="l517yxbln"/><path class="rzfubwb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quic-duotone-thin" /></template>
<style>
.a78831x8h {
  d: path("M2 5h6l4 4");
}

.eimg1ibhu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jm_ntdbid {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 5h6l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l517yxbln {
  d: path("M12 9v6");
}

.lg40ofb3n {
  d: path("M2 19h6l4 -4");
}

.rzfubwb2e {
  d: path("M12 12h10");
}

.sz5he4mqt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vhdygzbly {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h6l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
