<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="famncybwn"/><path class="rlkjycbtw"/><path class="du_3_4tit"/><path class="rvwqxxbhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:significance-test-outline-thin" /></template>
<style>
.du_3_4tit {
  d: path("M4 21.5h16");
}

.famncybwn {
  d: path("M7 8v11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rlkjycbtw {
  d: path("M17 12v7");
}

.rvwqxxbhr {
  d: path("m9.5 4.5 2 2L15 3");
}

</style>
