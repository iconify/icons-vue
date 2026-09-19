<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk03i7b2p"/><path class="hc_fmdbkf"/><path class="es0f9lbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-install-desktop" /></template>
<style>
.es0f9lbiz {
  fill: currentColor;
  d: path("M18 10.17V3h-2v7.17l-2.59-2.58L12 9l5 5l5-5l-1.41-1.41z");
}

.hc_fmdbkf {
  fill: currentColor;
  d: path("M20 17H4V5h9V3H4c-1.11 0-2 .89-2 2v12a2 2 0 0 0 2 2h4v2h8v-2h4c1.1 0 2-.9 2-2v-5.17l-2 2z");
}

.tk03i7b2p {
  fill: currentColor;
  d: path("M14.83 9L16 10.17zM4 17h16v-3.17l-3 3L9.17 9L13 5.17V5H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
