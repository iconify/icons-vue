<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bx-s88bhb"/><path class="o5f2izbvn"/><path class="dug30ossy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nmx-background" /></template>
<style>
.bx-s88bhb {
  fill: var(--svg-color--00a0ff, #00a0ff);
  d: path("M24 0H0v24h24z");
}

.dug30ossy {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.004 20a8.006 8.006 0 0 0 7.931-9.007h-1.391a.73.73 0 0 0-.52.216l-4.754 4.403a1.332 1.332 0 0 1-2.267-.966v-3.943l-3.948 3.713c-.495.465-1.15.575-1.826.575h-.65C5.769 17.933 8.702 20 12.004 20");
}

.ft5dv1b6b {
  fill: none;
}

.o5f2izbvn {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.064 12.994a8.006 8.006 0 0 1 15.361-4.003h-.88a2.65 2.65 0 0 0-1.862.75l-3.678 3.754V9.392c0-.8-.65-1.391-1.336-1.401c-.325 0-.66.11-.935.37l-4.989 4.428a.74.74 0 0 1-.51.205z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
