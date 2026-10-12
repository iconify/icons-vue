<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tic28wa9c"/><path class="jgfqx_bhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:maple-leaf-flag-sharp" /></template>
<style>
.jgfqx_bhk {
  d: path("m12.11 9.22l.62 1.23l.11.23l.22-.12l.61-.3l.22-.11l-.04.25l-.24 1.6l-.04.25l.2-.15l.87-.64l.2-.16l.21.13l.62.38l.21.13l-.11.22l-.4.81l-.12.23l.16.19l.11.13l.16.2l-.23.11l-1.65.83l-.23.11l.07.24l.08.25l.07.24l-.25-.05l-1.3-.31l-.24-.05l-.24.05l-1.3.31l-.25.05l.07-.24l.08-.25l.07-.24l-.23-.11l-1.65-.83l-.23-.11l.16-.2l.11-.13l.16-.19l-.12-.23l-.4-.81l-.11-.22l.21-.13l.62-.38l.21-.13l.2.16l.87.64l.2.15l-.04-.25l-.24-1.6l-.04-.25l.22.11l.61.3l.22.12l.11-.23l.62-1.23L12 9z");
}

.tic28wa9c {
  d: path("M2.75 5h18.5v14H2.75zm3 .75v12.5m12.5-12.5v12.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
