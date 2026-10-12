<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ohxdrbbbi"/><path class="avgh_-bpf"/><path class="w0-28b8kv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mihrab-sharp" /></template>
<style>
.avgh_-bpf {
  d: path("M7.75 21V11c0-2.5 1.75-4.5 4.25-6.25C14.5 6.5 16.25 8.5 16.25 11v10M12 8.75V11");
}

.ohxdrbbbi {
  d: path("M3.75 2.75h16.5v18.5H3.75z");
}

.w0-28b8kv {
  d: path("M10.25 11h3.5l-1 2.75h-1.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
