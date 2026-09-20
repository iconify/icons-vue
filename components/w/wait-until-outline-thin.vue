<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ppivcbbzp"/><path class="t87ohzbeq"/><path class="qjej79sen"/><path class="qd0z4jbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wait-until-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.qd0z4jbov {
  d: path("M16.5 9.5 19 12l-2.5 2.5");
}

.qjej79sen {
  d: path("M12.5 12H17");
}

.t87ohzbeq {
  d: path("M9 4v16");
}

</style>
