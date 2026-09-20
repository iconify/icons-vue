<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="p6-9d6bod"/><path class="pr4uw_bxm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ubsn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.p6-9d6bod {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.667 14.334L8.333 11V9.667L13.666 13z");
}

.pr4uw_bxm {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.333 9.667H20V11H8.333zm5.334 4.666H4V13h9.667z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
