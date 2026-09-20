<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="kacwlpbxe"/><path class="s0kvwubow"/><path class="nvd26nitq"/><path class="xgrfb-bqu"/><path class="he7cpnbxn"/><path class="ky10s_bai"/><path class="ru0la3bku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-wrap-duotone-thin" /></template>
<style>
.earhjk-cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.he7cpnbxn {
  d: path("M3 12h14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kacwlpbxe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ky10s_bai {
  d: path("M17 12v3h-7");
}

.nvd26nitq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.5 12.5 10 15l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ru0la3bku {
  d: path("M12.5 12.5 10 15l2.5 2.5");
}

.s0kvwubow {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 12v3h-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
