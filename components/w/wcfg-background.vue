<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mumfproca"/><path class="p7hmj6b3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wcfg-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.p7hmj6b3b {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.013 13.265c0 1.364.344 2.648.949 3.777l-.9.45A9.002 9.002 0 0 1 20 7.584l-.76.65A8.003 8.003 0 0 0 5.014 13.26zm7.753 5.49a5.493 5.493 0 0 1-5.25-5.352a5.495 5.495 0 0 1 9.821-3.525l.755-.65a6.495 6.495 0 1 0-5.326 10.527V18.75zm2.413-3.432a2.988 2.988 0 0 1-5.17-2.058a2.997 2.997 0 0 1 5.45-1.728l.76-.65a3.991 3.991 0 0 0-7.21 2.373a3.996 3.996 0 0 0 6.77 2.878l-.6-.82z");
}

</style>
