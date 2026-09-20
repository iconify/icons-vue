<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bnoz5_bvj"/><path class="vsnwypbyw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sfp-background" /></template>
<style>
.bnoz5_bvj {
  fill: var(--svg-color--4b21ef, #4b21ef);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vsnwypbyw {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.716 4.542a1.83 1.83 0 0 1 1.3-.54h8.981l-3.848 4H8.7c-.47 0-.7.23-.7.699v6.273L4.307 11.43a1.05 1.05 0 0 1 0-1.484zM15.299 16H7.85l-3.848 3.998h8.982c.49 0 .95-.195 1.3-.54l5.408-5.403a1.047 1.047 0 0 0 0-1.484l-3.694-3.544V15.3c0 .47-.23.7-.7.7");
}

</style>
