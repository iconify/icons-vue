<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vyks9vbfn"/><path class="t12-ippwj"/><path class="fxnzc9b-v"/><path class="cnmqodbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:time-travel-query-outline-regular" /></template>
<style>
.cnmqodbos {
  d: path("M13 13h4");
}

.fxnzc9b-v {
  d: path("M12 9v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t12-ippwj {
  d: path("M7 13a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
