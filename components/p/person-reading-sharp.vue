<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="wijmr5spd"/><path class="cpf79886a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-reading-sharp" /></template>
<style>
.cpf79886a {
  d: path("M12 13c-1.75-1.25-4-1.75-7.25-1.75v7.5c3.25 0 5.5.5 7.25 1.75c1.75-1.25 4-1.75 7.25-1.75v-7.5c-3.25 0-5.5.5-7.25 1.75Zm0 .25v6.5");
}

.wijmr5spd {
  cx: 12px;
  cy: 5.75px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
