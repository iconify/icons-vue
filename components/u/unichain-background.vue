<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="sn8bgzebf"/><path class="clvbvt3at"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:unichain-background" /></template>
<style>
.clvbvt3at {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 11.848A7.847 7.847 0 0 1 12.152 4h-.304v7.848H4v.304A7.847 7.847 0 0 1 11.848 20h.304v-7.848H20z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sn8bgzebf {
  fill: var(--svg-color--f50db4, #f50db4);
  d: path("M24 0H0v24h24z");
}

</style>
