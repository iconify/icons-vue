<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxy07wbdf"/><path class="eu9kkgbdm"/><path class="x3jqftbaj"/><path class="r3faxubne"/><path class="weza57brb"/><path class="al6h6yb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reorder-outline-thin" /></template>
<style>
.al6h6yb3y {
  d: path("m2 18 2 2 2 -2");
}

.eu9kkgbdm {
  d: path("M9 12h12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r3faxubne {
  d: path("M4 4v16");
}

.sxy07wbdf {
  d: path("M9 7h12");
}

.weza57brb {
  d: path("m2 6 2 -2 2 2");
}

.x3jqftbaj {
  d: path("M9 17h12");
}

</style>
