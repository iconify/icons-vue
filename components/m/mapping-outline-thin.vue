<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzn4jmbzj"/><path class="yw0xzbbmi"/><path class="n8h0kccut"/><path class="wl2374scp"/><path class="a04thmuhx"/><path class="o3p-ebloq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mapping-outline-thin" /></template>
<style>
.a04thmuhx {
  d: path("M8 12h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n8h0kccut {
  d: path("M4 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.o3p-ebloq {
  d: path("M8 18h10");
}

.wl2374scp {
  d: path("M8 6h10");
}

.xzn4jmbzj {
  d: path("M4 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.yw0xzbbmi {
  d: path("M4 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
