<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f4aw46bgq"/><path class="cin6o6p9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-plus-duotone" /></template>
<style>
.cin6o6p9o {
  d: path("M12 8L12 14M9 11L15 11");
}

.f4aw46bgq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2 C17.8553 2 23 5.8327 23 11 C23 16.1673 17.8553 20 12 20 C11.2351 20 10.4723 19.9337 9.7236 19.8047 L5.4385 21.8984 C5.1434 22.0425 4.7961 22.0329 4.5098 21.8721 C4.2235 21.7112 4.0344 21.4197 4.0039 21.0928 L3.6084 16.8252 C1.9521 15.2269 1 13.1718 1 11 C1 5.8327 6.1447 2 12 2 Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
