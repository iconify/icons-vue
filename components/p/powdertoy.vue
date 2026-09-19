<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s6_emfw_a"/><circle class="rue0xvhlh"/><circle class="in9vi2s6h"/><circle class="c8ffk1d-y"/><circle class="btfn83ahf"/><circle class="t7kywzbya"/><circle class="ahh5utb8z"/><circle class="bejd6bb9q"/><circle class="s96ssyb5m"/><circle class="ous2mdbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:powdertoy" /></template>
<style>
.ahh5utb8z {
  cx: 24.259px;
  cy: 23.796px;
  r: 0.75px;
  fill: currentColor;
}

.bejd6bb9q {
  cx: 24.259px;
  cy: 6.335px;
  r: 0.75px;
  fill: currentColor;
}

.btfn83ahf {
  cx: 28.922px;
  cy: 25.816px;
  r: 0.75px;
  fill: currentColor;
}

.c8ffk1d-y {
  cx: 24.259px;
  cy: 19.431px;
  r: 0.75px;
  fill: currentColor;
}

.in9vi2s6h {
  cx: 24.259px;
  cy: 15.066px;
  r: 0.75px;
  fill: currentColor;
}

.ous2mdbvg {
  cx: 16.489px;
  cy: 28.578px;
  r: 0.75px;
  fill: currentColor;
}

.rue0xvhlh {
  cx: 24.259px;
  cy: 10.701px;
  r: 0.75px;
  fill: currentColor;
}

.s6_emfw_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.996 42.415H6.004L24.26 26.497Z");
}

.s96ssyb5m {
  cx: 31.14px;
  cy: 28.578px;
  r: 0.75px;
  fill: currentColor;
}

.t7kywzbya {
  cx: 19.294px;
  cy: 26.736px;
  r: 0.75px;
  fill: currentColor;
}

</style>
