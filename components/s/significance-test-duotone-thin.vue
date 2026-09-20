<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wszxxccgq"/><path class="ei-4ftbit"/><path class="i6yllfq7b"/><path class="eexhscvig"/><path class="famncybwn"/><path class="rlkjycbtw"/><path class="du_3_4tit"/><path class="rvwqxxbhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:significance-test-duotone-thin" /></template>
<style>
.du_3_4tit {
  d: path("M4 21.5h16");
}

.eexhscvig {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 4.5 2 2L15 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ei-4ftbit {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.i6yllfq7b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rlkjycbtw {
  d: path("M17 12v7");
}

.rvwqxxbhr {
  d: path("m9.5 4.5 2 2L15 3");
}

.wszxxccgq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 8v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
