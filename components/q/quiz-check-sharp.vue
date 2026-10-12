<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ohxdrbbbi"/><circle class="amfo-fh-v"/><circle class="kdylvcbxp"/><path class="loy81tbxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quiz-check-sharp" /></template>
<style>
.amfo-fh-v {
  cx: 8.25px;
  cy: 8.5px;
  r: 1.5px;
}

.kdylvcbxp {
  cx: 8.25px;
  cy: 15.5px;
  r: 1.5px;
}

.loy81tbxd {
  d: path("M12 8.5h4.5m-4.5 7h4.5");
}

.ohxdrbbbi {
  d: path("M3.75 2.75h16.5v18.5H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
