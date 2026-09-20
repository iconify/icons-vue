<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nckgicb_c"/><path class="pyb-dybxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stpt" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nckgicb_c {
  fill: var(--svg-color--24aae1, #24aae1);
  d: path("M19.313 3H12l-7.312 9H12z");
}

.pyb-dybxv {
  fill: var(--svg-color--000, #000);
  d: path("M19.313 12H12l-7.312 9H12z");
}

</style>
