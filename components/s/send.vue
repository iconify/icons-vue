<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG91DPIcrk)" class="hd3cxutml"/><defs><linearGradient id="SVG91DPIcrk" x1="12" x2="12" y1="5.1" y2="18.3" gradientUnits="userSpaceOnUse"><stop class="efnpo_7-d"/><stop offset=".28" class="m517v6bmw"/><stop offset=".58" class="a1-lmabet"/><stop offset=".78" class="q1zoetbhi"/><stop offset="1" class="h20629l3o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:send" /></template>
<style>
.a1-lmabet {
  stop-color: var(--svg-color--846b52, #846b52);
}

.efnpo_7-d {
  stop-color: var(--svg-color--fdf6eb, #fdf6eb);
}

.ft5dv1b6b {
  fill: none;
}

.h20629l3o {
  stop-color: var(--svg-color--dfccaf, #dfccaf);
}

.hd3cxutml {
  d: path("M20.4 8.1H6.6v-3h10.734c1.02 0 3.066.6 3.066 3m-13.8 0v1.542c0 .258.15.858.75.858H18c1.002 0 3 .378 3 2.226v3.858c0 .516-.6 2.316-3 2.316H6c-1.002 0-3-.504-3-2.97h14.25c.252 0 .75-.312.75-.93v-.6c0-.258-.15-.9-.75-.9H5.1c-.75 0-1.5-.306-1.5-1.542V8.1z");
}

.m517v6bmw {
  stop-color: var(--svg-color--cfb89a, #cfb89a);
}

.q1zoetbhi {
  stop-color: var(--svg-color--ad9173, #ad9173);
}

</style>
