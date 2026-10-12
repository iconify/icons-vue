<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x6bn03b3e"/><path class="o0s9dt16f"/><path class="hzyzgbc0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pen-paper-sharp" /></template>
<style>
.hzyzgbc0c {
  d: path("m13.67 16.72l-1.39-1.39l-.42-.42l-.31.51l-1.43 2.37l-.31.51l.42.42l.05.05l.42.42l.51-.31l2.37-1.43l.51-.31zm3.88-3.04l-2.23-2.23");
}

.o0s9dt16f {
  d: path("m20.31 9.5l-.81-.81l-.71-.71l-.71.71l-5.51 5.51l-.71.71l.71.71l.81.81l.71.71l.71-.71l5.51-5.51l.71-.71z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x6bn03b3e {
  d: path("M3.75 2.75h13v18.5h-13zm3.5 4.5h6m-6 3.5h3.5");
}

</style>
