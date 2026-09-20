<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gg7e2r9pr"/><path class="upkqslbhj"/><path class="eiak_gzql"/><path class="d88esignp"/><path class="nl66y9men"/><path class="f4b4cfbbo"/><path class="x-ycuabua"/><path class="i6okezb6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-care-duotone-bold" /></template>
<style>
.d88esignp {
  d: path("M8 13h8v8H8Z");
}

.eiak_gzql {
  fill: currentColor;
  d: path("M12 8c0 -3 3 -5 7 -5 0 3 -3 5 -7 5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f4b4cfbbo {
  d: path("M12 13V8");
}

.gg7e2r9pr {
  fill: currentColor;
  d: path("M8 13h8v8H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i6okezb6k {
  d: path("M12 8c0 -3 3 -5 7 -5 0 3 -3 5 -7 5");
}

.nl66y9men {
  d: path("M6 16h12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.upkqslbhj {
  fill: currentColor;
  d: path("M12 8c0 -4 -3 -6 -7 -6 0 4 3 6 7 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x-ycuabua {
  d: path("M12 8c0 -4 -3 -6 -7 -6 0 4 3 6 7 6");
}

</style>
