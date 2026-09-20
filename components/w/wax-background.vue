<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="koktlqfeg"/><path class="lhvtk_pcx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wax-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.koktlqfeg {
  fill: var(--svg-color--f78e1e, #f78e1e);
  d: path("M24 0H0v24h24z");
}

.lhvtk_pcx {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.433 10.333l-.766.657l.783.677L20 10.333zm-4.766-1l2.966 2.65l-1.133.684l-2-2.334h-1.333l-3.5 4.334H10l2.833-3.334l.887 1h-1.053L12 13h2.22l.613.667h1.334l1.333-1l1.167 1H20l-5-4.334zm-4.334 1l-.666 2l-.667-2H6.667l-.667 2l-.667-2H4l1.333 3.334h1.334l.666-2l.667 2h1.333l1.334-3.334z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
