<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nkjy9vb4n"/><path class="qpf3-4b8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stream-sharp" /></template>
<style>
.nkjy9vb4n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.4 21.25c.44-.47 2.15-1.89 2.68-2.83l.722-1.27l-.182-1.57c-.11-.94-.78-1.89-1.2-2.83S8.33 10.86 8.1 9.92l-.371-1.531l.331-1.309c.24-.94 1.23-2.36 1.48-2.83m8.36 17c.22-.47 1.26-1.89 1.35-2.83l.119-1.253l-.919-1.587c-.55-.94-1.66-1.89-2.53-2.83c-.86-.94-1.98-1.89-2.66-2.83l-1.101-1.561l-.269-1.279c-.2-.94.13-2.36.15-2.83m1.8 15.64c.1-.16.44-.64.6-.96s.29-.65.36-.97l.109-.498L14.88 17l-.013-.427l-.167-.533c-.1-.32-.24-.65-.41-.97s-.5-.8-.6-.96");
}

.qpf3-4b8n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.19 16.15h.01m8.22-5.44h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
