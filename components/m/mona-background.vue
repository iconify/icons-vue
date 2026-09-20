<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lcf_7sbnl"/><path class="fw8pa3syh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mona-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fw8pa3syh {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.024 9.928L16.88 4.8l-2.24 3.528a11.3 11.3 0 0 0-5.28 0L7.12 4.8L5.976 9.928C4.752 10.912 4 12.2 4 13.608c0 3.088 3.584 5.592 8 5.592s8-2.504 8-5.6c0-1.4-.752-2.688-1.976-3.672M7.552 12h-.528l1.296-1.5h.952zm4.4 3.944l-2.208-3.896l.544-.312l.496.764H13.2l.52-.772l.536.32l-2.296 3.896zM16.448 12l-1.72-1.5h.96l1.296 1.5zm-4.48 2.696L11.008 13h2.003z");
}

.lcf_7sbnl {
  fill: var(--svg-color--d0b47a, #d0b47a);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
