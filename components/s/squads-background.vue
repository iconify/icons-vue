<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="ar-qg8ssn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:squads-background" /></template>
<style>
.ar-qg8ssn {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.596 8.285l-2.168-2.167l-1.71-1.713A1.4 1.4 0 0 0 14.742 4H9.26a1.4 1.4 0 0 0-.977.405l-1.709 1.71l-2.167 2.167A1.38 1.38 0 0 0 4 9.26v5.482a1.38 1.38 0 0 0 .406.979l3.876 3.877a1 1 0 0 0 .102.088c.247.202.556.312.875.313h5.482c.32 0 .629-.111.876-.313l.101-.088l3.877-3.877a1.38 1.38 0 0 0 .405-.98V9.262a1.4 1.4 0 0 0-.404-.976m-1.71 3.723v4.596a1.29 1.29 0 0 1-1.292 1.286H7.401a1.287 1.287 0 0 1-1.288-1.288V7.408A1.29 1.29 0 0 1 7.4 6.118h9.193a1.29 1.29 0 0 1 1.289 1.29v4.601z");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
