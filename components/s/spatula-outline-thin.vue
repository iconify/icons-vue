<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gvgmi5cyl"/><path class="mcs12xbpj"/><path class="ubusnobws"/><path class="e7fjltb5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spatula-outline-thin" /></template>
<style>
.e7fjltb5i {
  d: path("M12 13v8");
}

.gvgmi5cyl {
  d: path("M6 6h12v7H6Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcs12xbpj {
  d: path("M10 8v3");
}

.ubusnobws {
  d: path("M14 8v3");
}

</style>
