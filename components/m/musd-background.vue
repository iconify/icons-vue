<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="of3nnh91f"/><path class="hk2oyk2re"/><path class="czxe9fbci"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:musd-background" /></template>
<style>
.czxe9fbci {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.245 8h2.735s.03-.165.02-.415C15.96 6.765 15.6 5 11.924 5c-4.07 0-4.15 2.455-4.15 2.82c0 .285-.166 2.095 2.23 2.7c2.4.605 3.494.665 3.494 1.55c0 .89-.774 1.15-1.42 1.15c-.65 0-1.58-.065-1.58-1.22h-3s-.21 3 4.426 3c4.634 0 4.575-2.8 4.575-3.225c0-.4-.09-1.965-2.72-2.615c-2.625-.65-3.28-.66-3.28-1.575c0-.75 1.04-.835 1.55-.835c.365 0 1.194-.005 1.194 1.25");
}

.ft5dv1b6b {
  fill: none;
}

.hk2oyk2re {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.5 17h15v3h-15zM11 4h1.5v11.5H11z");
}

.of3nnh91f {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
