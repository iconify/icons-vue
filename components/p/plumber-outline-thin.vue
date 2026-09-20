<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k74vnib1e"/><path class="fqjewfbna"/><path class="lna_zyjca"/><path class="tukmg9l1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:plumber-outline-thin" /></template>
<style>
.fqjewfbna {
  d: path("M2 16a4 4 0 0 1 8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k74vnib1e {
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.lna_zyjca {
  d: path("m13 20 4 -4");
}

.tukmg9l1f {
  d: path("M21.12 15.12a3 3 0 1 1 0 -4.24");
}

</style>
