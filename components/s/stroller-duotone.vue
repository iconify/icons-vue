<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i95z05d7d"/><path class="we8l4ob7a"/><path class="dq4pl3bbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stroller-duotone" /></template>
<style>
.dq4pl3bbw {
  d: path("M9 20C9 21.1046 8.1046 22 7 22C5.8954 22 5 21.1046 5 20C5 18.8954 5.8954 18 7 18C8.1046 18 9 18.8954 9 20ZM17 20C17 21.1046 16.1046 22 15 22C13.8954 22 13 21.1046 13 20C13 18.8954 13.8954 18 15 18C16.1046 18 17 18.8954 17 20Z");
}

.i95z05d7d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 9.099L20 10C20 12.7614 17.7614 15 15 15L7 15C4.2386 15 2 12.7614 2 10L2 9C2 8.4477 2.4477 8 3 8L18.1802 8L18.8586 4.6077C19.0456 3.6729 19.8664 3 20.8198 3L21 3C21.5523 3 22 3.4477 22 4C22 4.5523 21.5523 5 21 5L20.8198 5L20 9.099Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.we8l4ob7a {
  fill: currentColor;
  d: path("M2 9C1.9994 5.8872 3.8044 3.0566 6.6269 1.744C7.6834 1.2525 8.8348 0.9986 10 1C10.5523 1 11 1.4477 11 2L11 9C11 9.5523 10.5523 10 10 10L3 10C2.4477 10 2 9.5523 2 9Z");
  stroke: none;
}

</style>
