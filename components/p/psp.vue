<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG6eyl7CFZ)" clip-rule="evenodd" class="cwzs-dbel"/><defs><linearGradient id="SVG6eyl7CFZ" x1="16.343" x2="10.295" y1="5.523" y2="19.535" gradientUnits="userSpaceOnUse"><stop class="ts3-bsa0f"/><stop offset="1" class="mt-tjbjbu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:psp" /></template>
<style>
.cwzs-dbel {
  fill-rule: evenodd;
  d: path("M3 4.688h7.875l-3.926 6.75zm1.294 14.625H21L12.624 4.688zm3.588-2.25h9.36l-4.69-8.438z");
}

.ft5dv1b6b {
  fill: none;
}

.mt-tjbjbu {
  stop-color: var(--svg-color--185bef, #185bef);
}

.ts3-bsa0f {
  stop-color: var(--svg-color--568eff, #568eff);
}

</style>
