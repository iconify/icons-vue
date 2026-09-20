<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0n63pb2v"/><path class="v_bddgbtn"/><path class="sfjortb-o"/><path class="q7h9nybxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-tier-outline-regular" /></template>
<style>
.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q7h9nybxu {
  d: path("M16 9v3");
}

.sfjortb-o {
  d: path("M12 7v5");
}

.v_bddgbtn {
  d: path("M8 5v7");
}

</style>
