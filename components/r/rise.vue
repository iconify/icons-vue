<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGuCXJ3b2t)" class="qzi8rdlox"/><defs><linearGradient id="SVGuCXJ3b2t" x1="3.002" x2="21.002" y1="10.451" y2="12.11" gradientUnits="userSpaceOnUse"><stop class="cmwuixjqx"/><stop offset="1" class="ion3qacuq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rise" /></template>
<style>
.cmwuixjqx {
  stop-color: var(--svg-color--cc1a3c, #cc1a3c);
}

.ft5dv1b6b {
  fill: none;
}

.ion3qacuq {
  stop-color: var(--svg-color--ff9a2e, #ff9a2e);
}

.qzi8rdlox {
  d: path("M14.463 20.995a9.15 9.15 0 0 0 6.534-8.824C20.997 7.112 16.97 3 12 3s-8.998 4.105-8.998 9.172c0 4.194 2.761 7.731 6.535 8.828l1.9-11.252l-4.78 3.57l-.28-.286L12 5.249l5.623 7.783l-.281.281l-4.78-3.565z");
}

</style>
