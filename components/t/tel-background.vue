<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jrbajb4uh"/><path class="w6l4sqb6r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tel-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jrbajb4uh {
  fill: var(--svg-color--14c8ff, #14c8ff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w6l4sqb6r {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.268 8.382a2.19 2.19 0 0 1 .716 1.881l-1.091 6.024a2.24 2.24 0 0 1-1.331 1.536l-5.939 2.082a2.37 2.37 0 0 1-2.046-.35l-4.849-3.933a2.18 2.18 0 0 1-.71-1.886l1.086-6.024a2.24 2.24 0 0 1 1.33-1.536l5.945-2.082a2.37 2.37 0 0 1 2.041.35zm-5.053 2.617l.24-1h-2.267l.32-2.002h-.73c-.53.81-1.3 1.65-2.201 2.001l-.205 1h1.306s-.446 1.577-.556 2.137c-.28 1.426.215 2.367 1.3 2.367h1.832l.23-1h-1.536c-.68 0-.64-.376-.51-1.037l.51-2.466z");
}

</style>
