<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v6idbfb-b"/><path class="oqj-o0b2r"/><path class="owfn5sxxm"/><path class="x7yzkkbqs"/><path class="xroalcbzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sofa-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oqj-o0b2r {
  d: path("M5 14h14");
}

.owfn5sxxm {
  d: path("M12 8v6");
}

.v6idbfb-b {
  d: path("M5 19V8h14v11");
}

.x7yzkkbqs {
  d: path("M2 19v-5h3");
}

.xroalcbzh {
  d: path("M22 19v-5h-3");
}

</style>
