<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ckawxab4i"/><path class="d8abqfbpc"/><path class="rdv9wsbxa"/><path class="u78lc2bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shade-outline-thin" /></template>
<style>
.ckawxab4i {
  d: path("m4 11 8 -8 8 8");
}

.d8abqfbpc {
  d: path("M3 11h18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rdv9wsbxa {
  d: path("M12 11v9");
}

.u78lc2bnx {
  d: path("M6 20h12");
}

</style>
