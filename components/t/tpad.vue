<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG1PlEudGx)" class="yka7gt64k"/><defs><linearGradient id="SVG1PlEudGx" x1="11.415" x2="22.82" y1="18.81" y2="14.225" gradientUnits="userSpaceOnUse"><stop class="s-hug556i"/><stop offset="1" class="wtn33i8_k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tpad" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s-hug556i {
  stop-color: var(--svg-color--fc01c2, #fc01c2);
}

.wtn33i8_k {
  stop-color: var(--svg-color--6d138e, #6d138e);
}

.yka7gt64k {
  d: path("m11.875 21l.01-18L4.5 6.43l2.015 1.185l3.985-1.82v14.4c.225.14.455.27.685.4zm1.625-.8l-1.38.8V3l7.38 3.43l-1.99 1.205L13.5 5.75zm-9-13.04c.32.19.66.38 1 .57s.68.38 1 .57v7.19l3.5 2.08v2.25l-5.5-3.205zm14 .57c.34-.19.68-.38 1-.57v9.455c-.915.535-1.835 1.08-2.75 1.63L14 19.87v-2.3c.6-.35 1.175-.695 1.75-1.04a81 81 0 0 1 1.75-1.04V8.3c.32-.19.66-.38 1-.57");
}

</style>
