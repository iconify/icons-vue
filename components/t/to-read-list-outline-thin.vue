<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u1nlm01-r"/><path class="fqbma974b"/><path class="eq1ozwbjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:to-read-list-outline-thin" /></template>
<style>
.eq1ozwbjq {
  d: path("M3 21h14");
}

.fqbma974b {
  d: path("M6 13h14v4H6Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u1nlm01-r {
  d: path("M3 6h14v4H3Z");
}

</style>
