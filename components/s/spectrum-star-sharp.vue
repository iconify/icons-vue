<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h69e86olk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spectrum-star-sharp" /></template>
<style>
.h69e86olk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.14 3.07l1.03 2.31l.14.32l.35.03l2.51.27l.35.03l-.26.24l-1.88 1.68l-.26.24l.07.34l.53 2.47l.07.34l-.3-.17l-2.19-1.26l-.3-.18l-.3.18l-2.19 1.26l-.3.17l.07-.34l.53-2.47l.07-.34l-.26-.24l-1.88-1.68l-.26-.24l.35-.03l2.51-.27l.35-.03l.14-.32l1.03-2.31l.14-.32zM2.75 14.75h18.5v6.5H2.75zm3.75 0v6.5m2.75-6.5v6.5m5.25-6.5v6.5m3.5-6.5v6.5");
}

</style>
