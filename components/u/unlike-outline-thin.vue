<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lkje5bbsk"/><path class="fk8qv-tpl"/><path class="c3lntibww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:unlike-outline-thin" /></template>
<style>
.c3lntibww {
  d: path("m22 9 -7 7");
}

.fk8qv-tpl {
  d: path("m15 9 7 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkje5bbsk {
  d: path("M2 9a2.5 2.5 0 0 1 5 0 2.5 2.5 0 0 1 5 0l-5 5Z");
}

</style>
