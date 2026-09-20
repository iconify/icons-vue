<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zaau21ski"/><path class="vj8si9dha"/><path class="fa2e7y2tg"/><path class="wfg0vmbgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:syntax-outline-thin" /></template>
<style>
.fa2e7y2tg {
  d: path("M4 17h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vj8si9dha {
  d: path("m16 4 4 4 -4 4");
}

.wfg0vmbgy {
  d: path("M15 17h5");
}

.zaau21ski {
  d: path("M8 4 4 8l4 4");
}

</style>
