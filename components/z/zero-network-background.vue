<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f29raibzn"/><path class="e-xj4bbxl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zero-network-background" /></template>
<style>
.e-xj4bbxl {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4c-5.16 0-7.2 3.204-7.2 7.922C4.8 16.639 6.84 20 12 20s7.2-3.361 7.2-8.078C19.2 7.204 17.16 4 12 4m0 13.415c-2.353 0-3.571-1.403-3.94-3.765a.29.29 0 0 1 .284-.34h7.277c.176 0 .31.16.284.338c-.358 2.363-1.55 3.767-3.904 3.767m-3.687-6.666a.29.29 0 0 1-.284-.334c.327-2.456 1.547-3.83 3.972-3.83s3.617 1.375 3.933 3.832a.29.29 0 0 1-.284.332z");
}

.f29raibzn {
  fill: var(--svg-color--fe5161, #fe5161);
  d: path("M0 0h24v24H0z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
