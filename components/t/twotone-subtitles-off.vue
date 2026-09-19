<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psj02laow"/><path class="s-50cgift"/><path class="tfmatbbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-subtitles-off" /></template>
<style>
.psj02laow {
  fill: currentColor;
  d: path("m8.83 6l4 4H18v2h-3.17L20 17.17V6zm6.34 12l-2-2H6v-2h5.17L8 10.83V12H6v-2h1.17L4 6.83V18z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s-50cgift {
  fill: currentColor;
  d: path("M18 10h-5.17l2 2H18z");
}

.tfmatbbdl {
  fill: currentColor;
  d: path("M20 4H6.83l2 2H20v11.17l1.76 1.76c.15-.28.24-.59.24-.93V6c0-1.1-.9-2-2-2M1.04 3.87l1.2 1.2C2.09 5.35 2 5.66 2 6v12c0 1.1.9 2 2 2h13.17l2.96 2.96l1.41-1.41L2.45 2.45zM4 6.83L7.17 10H6v2h2v-1.17L11.17 14H6v2h7.17l2 2H4z");
}

</style>
