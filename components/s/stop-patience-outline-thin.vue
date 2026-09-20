<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pesxdybze"/><path class="qxju3_sgm"/><path class="eky6twzzr"/><path class="trk8friyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stop-patience-outline-thin" /></template>
<style>
.eky6twzzr {
  d: path("M16.5 9.5V12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pesxdybze {
  d: path("M3 12h7");
}

.qxju3_sgm {
  d: path("M12.5 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.trk8friyx {
  d: path("M16.5 12H19");
}

</style>
