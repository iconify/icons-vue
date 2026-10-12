<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xsafl7ggx"/><circle class="q72b48b9q"/><path class="q2mrbpbpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:master-key-sharp" /></template>
<style>
.q2mrbpbpj {
  d: path("M12 15.75h9.25V19m-3.5-3.25v2.5");
}

.q72b48b9q {
  cx: 7.5px;
  cy: 15.75px;
  r: 4.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xsafl7ggx {
  d: path("M4 7.9V4l.26.23l1.48 1.29l.26.23l.19-.29l1.12-1.67l.19-.29l.19.29l1.12 1.67l.19.29l.26-.23l1.48-1.29L11 4v4.25H4z");
}

</style>
