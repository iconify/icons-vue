<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bfre3yvjw"/><path class="q00-sb0vc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:world-map-sharp" /></template>
<style>
.bfre3yvjw {
  d: path("M2.75 6.25L9 4l6 2.25L21.25 4v13.75L15 20l-6-2.25L2.75 20Zm6.25 8v3.5m6-11.5V10");
}

.q00-sb0vc {
  d: path("m7.35 7.9l.55-.3L9 7l1.1.6l.55.3l1.1.6l-.37 1.13l-.38 1.12l-1.24.16l-1.52.18l-1.24.16l-.33-1.21l-.09-.33l-.33-1.21zm6.39 5.42l2.77-.39l1.24-.18l-.11 1.24l-.03.27l-.11 1.24l-1.07.64l-.36.22L15 17l-1.09-.61l-.07-.03l-1.09-.61l-.12-1.12l-.13-1.13z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
