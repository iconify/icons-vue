<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGnunAEbEW)" class="bkst3lwlz"/><defs><linearGradient id="SVGnunAEbEW" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="dsv9qhbgl"/><stop offset="1" class="o53tdccfe"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tonic" /></template>
<style>
.bkst3lwlz {
  d: path("M3.6 3h10.8v4.8H3.6zm12 0h4.8v4.8h-4.8zm-1.2 6H9.6v12h4.8z");
}

.dsv9qhbgl {
  stop-color: var(--svg-color--000d34, #000d34);
}

.ft5dv1b6b {
  fill: none;
}

.o53tdccfe {
  stop-color: var(--svg-color--42243d, #42243d);
}

</style>
