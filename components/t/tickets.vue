<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nv5367b0y"/><circle class="hw-l8basm"/><path class="fzd3796uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tickets" /></template>
<style>
.fzd3796uh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.304 14.924H15.5v3.804m17 0v-3.804h-3.804m0 17H32.5V28.12m-14.68-3.589v5.054h5.054v-5.054Zm0-7.287v5.054h5.054v-5.054Zm7.287 0v5.054h5.054v-5.054Zm2.537 12.36a2.66 2.66 0 0 0 1.594-.965a3.85 3.85 0 0 0 .942-2.628v-1.48h-5.054v1.48h0a3.85 3.85 0 0 0 .942 2.628a2.66 2.66 0 0 0 1.575.965M15.5 28.12v3.804h3.804M31.051 4.5h-.603a1 1 0 0 0-.864.496l-.982 1.686a2 2 0 0 1-1.728.992h-5.748a2 2 0 0 1-1.728-.992l-.982-1.686a1 1 0 0 0-.864-.496h-.603");
}

.hw-l8basm {
  cx: 26.553px;
  cy: 6.087px;
  r: 0.75px;
  fill: currentColor;
}

.nv5367b0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.337 43.5H14.663a2 2 0 0 1-2-2v-35a2 2 0 0 1 2-2h18.674a2 2 0 0 1 2 2v35a2 2 0 0 1-2 2M21.098 6.042h3.628");
}

</style>
