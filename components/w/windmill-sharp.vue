<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="anpm10bof"/><path class="blpeiwbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:windmill-sharp" /></template>
<style>
.anpm10bof {
  d: path("m7.7 20.53l1.6-5.81l.2-.72h5l.2.72l1.6 5.81l.2.72h-9z");
}

.blpeiwbqh {
  d: path("M11 21.25v-3h2v3M8.25 3.75l7.5 7.5m0-7.5l-7.5 7.5M12 7.5V14");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
