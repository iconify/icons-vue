<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nuav6cq3b"/><path class="de4_krqzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:verified-sharp" /></template>
<style>
.de4_krqzo {
  d: path("M8.75 12.25L11 14.5l4.25-4.5");
}

.nuav6cq3b {
  d: path("m13.02 3.47l.92.65l1.03.72l1.23.21l1.11.2l1.23.21l.21 1.23l.2 1.11l.21 1.23l.72 1.03l.65.92l.72 1.02l-.72 1.02l-.65.92l-.72 1.03l-.21 1.23l-.2 1.11l-.21 1.23l-1.23.21l-1.11.2l-1.23.21l-1.03.72l-.92.65l-1.02.72l-1.02-.72l-.92-.65l-1.03-.72l-1.23-.21l-1.11-.2l-1.23-.21l-.21-1.23l-.2-1.11l-.21-1.23l-.72-1.03l-.65-.92L2.75 12l.72-1.02l.65-.92l.72-1.03l.21-1.23l.2-1.11l.21-1.23l1.23-.21l1.11-.2l1.23-.21l1.03-.72l.92-.65L12 2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
