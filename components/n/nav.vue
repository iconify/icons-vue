<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGdjVJ2doA)" clip-rule="evenodd" class="n8402lk-k"/><defs><linearGradient id="SVGdjVJ2doA" x1="21" x2="4.08" y1="3.6" y2="21.568" gradientUnits="userSpaceOnUse"><stop class="swqw-eaou"/><stop offset=".456" class="x2i2sniug"/><stop offset="1" class="szc7xzt4p"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nav" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n8402lk-k {
  fill-rule: evenodd;
  d: path("M7.56 4.08a1.2 1.2 0 0 0-2.16.72v6H4.2a1.2 1.2 0 1 0 0 2.4h1.2v6a1.2 1.2 0 1 0 2.4 0v-6h3.6l5.04 6.72a1.199 1.199 0 0 0 2.16-.72v-6h1.2a1.2 1.2 0 1 0 0-2.4h-1.2v-6a1.2 1.2 0 0 0-2.4 0v6h-3.6zm6.84 9.12l1.8 2.4v-2.4zm-4.8-2.4L7.8 8.4v2.4z");
}

.swqw-eaou {
  stop-color: var(--svg-color--0b88f6, #0b88f6);
}

.szc7xzt4p {
  stop-color: var(--svg-color--dd1eba, #dd1eba);
}

.x2i2sniug {
  stop-color: var(--svg-color--7152d7, #7152d7);
}

</style>
