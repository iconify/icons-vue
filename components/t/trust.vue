<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yonmz3idf"/><path fill="url(#SVGS7Lkadyu)" class="lh5mqrbmd"/><defs><linearGradient id="SVGS7Lkadyu" x1="17.948" x2="11.967" y1="1.74" y2="20.797" gradientUnits="userSpaceOnUse"><stop offset=".02" class="i53so8b0d"/><stop offset=".08" class="w6k954b6m"/><stop offset=".16" class="rofixpxoy"/><stop offset=".42" class="w6k954b6m"/><stop offset=".68" class="lq706wtdj"/><stop offset=".9" class="zd5jl2t-v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trust" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i53so8b0d {
  stop-color: var(--svg-color--00f, #00f);
}

.lh5mqrbmd {
  d: path("M20.1 5.6L12 3v18c5.786-2.4 8.1-7 8.1-9.6z");
}

.lq706wtdj {
  stop-color: var(--svg-color--0038ff, #0038ff);
}

.rofixpxoy {
  stop-color: var(--svg-color--48ff91, #48ff91);
}

.w6k954b6m {
  stop-color: var(--svg-color--0094ff, #0094ff);
}

.yonmz3idf {
  fill: var(--svg-color--0500ff, #0500ff);
  d: path("M3.9 5.6L12 3v18c-5.786-2.4-8.1-7-8.1-9.6z");
}

.zd5jl2t-v {
  stop-color: var(--svg-color--0500ff, #0500ff);
}

</style>
