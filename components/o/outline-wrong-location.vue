<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygnbibfsw"/><circle class="cbp_2nbuo"/><path class="mcybtfbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-wrong-location" /></template>
<style>
.cbp_2nbuo {
  cx: 12px;
  cy: 11px;
  r: 2px;
  fill: currentColor;
}

.mcybtfbrd {
  fill: currentColor;
  d: path("m22.54 2.88l-1.42-1.42L19 3.59l-2.12-2.13l-1.42 1.42L17.59 5l-2.13 2.12l1.42 1.42L19 6.41l2.12 2.13l1.42-1.42L20.41 5z");
}

.ygnbibfsw {
  fill: currentColor;
  d: path("M18 11v.2c0 2.34-1.95 5.44-6 9.14c-4.05-3.7-6-6.79-6-9.14C6 7.57 8.65 5 12 5c.34 0 .68.03 1 .08V3.06c-.33-.04-.66-.06-1-.06c-4.2 0-8 3.22-8 8.2c0 3.32 2.67 7.25 8 11.8c5.33-4.55 8-8.48 8-11.8V11z");
}

</style>
