<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y0v2plbik"/><path clip-rule="evenodd" class="vgp2v0zxv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sai-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vgp2v0zxv {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 0 0 6.163-13.101L6.898 18.163A7.97 7.97 0 0 0 12 20m-6.12-2.848L17.152 5.88A8 8 0 0 0 5.88 17.152");
}

.y0v2plbik {
  fill: var(--svg-color--21201d, #21201d);
  d: path("M24 0H0v24h24z");
}

</style>
