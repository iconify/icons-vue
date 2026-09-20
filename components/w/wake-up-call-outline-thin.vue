<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nqda50bqs"/><path class="fxnzc9b-v"/><path class="bh28pgoco"/><path class="fcb5akbfg"/><path class="txeai18yr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wake-up-call-outline-thin" /></template>
<style>
.bh28pgoco {
  d: path("M12 13h4");
}

.fcb5akbfg {
  d: path("m5 5 3 3");
}

.fxnzc9b-v {
  d: path("M12 9v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nqda50bqs {
  d: path("M4 13a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.txeai18yr {
  d: path("m19 5 -3 3");
}

</style>
