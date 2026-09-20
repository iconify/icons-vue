<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ykf_-sbak"/><path class="fwnwnrf-o"/><path class="ynmt0ob9o"/><path class="oz3eccbug"/><path class="ls_1jlbjr"/><path class="mhf9v2bnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scarf-duotone-thin" /></template>
<style>
.fwnwnrf-o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 8v10h4V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ls_1jlbjr {
  d: path("M7 8v10h4V8");
}

.mhf9v2bnf {
  d: path("M14 11v10h4V11");
}

.oz3eccbug {
  d: path("M7 8a5 5 0 0 1 10 0");
}

.ykf_-sbak {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 8a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ynmt0ob9o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 11v10h4V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
