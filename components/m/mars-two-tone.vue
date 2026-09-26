<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lmrsucqff"/><path class="o2133cbro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mars-two-tone" /></template>
<style>
.lmrsucqff {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 15C16 18.866 12.866 22 9 22C5.134 22 2 18.866 2 15C2 11.134 5.134 8 9 8C12.866 8 16 11.134 16 15Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o2133cbro {
  d: path("M15 15C15 18.3137 12.3137 21 9 21C5.6863 21 3 18.3137 3 15C3 11.6863 5.6863 9 9 9C12.3137 9 15 11.6863 15 15ZM15.5 3L20.5 3C20.7761 3 21 3.2239 21 3.5L21 8.5M13.2426 10.7574L20.4 3.6");
}

</style>
