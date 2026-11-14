<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jey4w3qun"/><path class="lkg9ylzgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-lottery" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jey4w3qun {
  d: path("M3 5.5h18V10a2 2 0 0 0 0 4v4.5H3V14a2 2 0 0 0 0-4Z");
}

.lkg9ylzgp {
  d: path("m12.5 9.375l.142.32a1.5 1.5 0 0 0 1.235.885l.55.05a.569.569 0 0 1 .323.995l-.36.315a1.5 1.5 0 0 0-.488 1.397l.106.583a.574.574 0 0 1-.883.58l-.293-.195a1.5 1.5 0 0 0-1.664 0l-.293.195a.574.574 0 0 1-.883-.58l.106-.583a1.5 1.5 0 0 0-.488-1.397l-.36-.315a.569.569 0 0 1 .323-.995l.55-.05a1.5 1.5 0 0 0 1.235-.885l.142-.32a.547.547 0 0 1 1 0");
}

</style>
