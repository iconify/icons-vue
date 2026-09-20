<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6nj2fbya"/><path class="qxnpdo0dk"/><path class="zuu1wnb1v"/><path class="o46_3ibvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:order-by-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.o46_3ibvz {
  d: path("M3 20h6");
}

.qxnpdo0dk {
  d: path("M3 10h14");
}

.zuu1wnb1v {
  d: path("M3 15h10");
}

</style>
