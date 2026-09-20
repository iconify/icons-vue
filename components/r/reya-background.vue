<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ijwe4gg6n"/><path class="jrf4_ob4y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:reya-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ijwe4gg6n {
  fill: var(--svg-color--08f06a, #08f06a);
  d: path("M24 0H0v24h24z");
}

.jrf4_ob4y {
  fill: var(--svg-color--000, #000);
  d: path("M8.798 14.025L7.515 11.55V6.495L6 4h6.098c3.629 0 5.749 1.839 5.749 4.99c0 2.145-1.006 3.678-2.885 4.444L18 20h-3.06l-2.71-5.975zm-1.283-7.53v5.056h4.583c1.77 0 2.82-.94 2.82-2.56c0-1.598-1.05-2.496-2.82-2.496z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
