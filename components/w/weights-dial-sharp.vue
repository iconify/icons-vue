<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="g1cmp1uny"/><path class="lz8j_nb_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:weights-dial-sharp" /></template>
<style>
.g1cmp1uny {
  cx: 12px;
  cy: 13.25px;
  r: 6.5px;
}

.lz8j_nb_a {
  d: path("m4.64 9l-1.08-.62m4.19-2.49l-.62-1.08M12 4.75V3.5m4.25 2.39l.63-1.08M19.36 9l1.08-.62M12 13.25l2.13-3.68");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
