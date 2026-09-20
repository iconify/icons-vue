<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="esolkqbpc"/><path class="d63c1ws2f"/><path class="hrg1ozfca"/><path class="c-pcdbceg"/><path class="dn5wogbzl"/><path class="qxclf1btn"/><path class="olx0yluil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rain-chance-duotone-thin" /></template>
<style>
.c-pcdbceg {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

.d63c1ws2f {
  fill: currentColor;
  d: path("M7.5 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dn5wogbzl {
  d: path("M7.5 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.esolkqbpc {
  fill: currentColor;
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrg1ozfca {
  fill: currentColor;
  d: path("M12.5 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.olx0yluil {
  d: path("M12.5 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qxclf1btn {
  d: path("m8 21 6 -6");
}

</style>
