<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xkw4r_b5w"/><path class="mdldinb9k"/><path class="z4ysap9ca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:white-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mdldinb9k {
  fill: var(--svg-color--dfdfdf, #dfdfdf);
  d: path("M13.85 5.62c.784-.55 1.59-.87 2.15-.87c2 0 4 1 4 4.5c0 3.1-4.31 6.98-6.86 9.215C15.57 16.18 19 12.63 19 9.75c0-3.5-1.94-4.5-3.876-4.5c-.35 0-.8.13-1.27.37zm-1.6 1.63c-1-1.75-2.365-2.5-4.25-2.5c-.865 0-2.06.33-2.92 1.285a3.88 3.88 0 0 1 2.295-.785c1.78 0 3.165 1.265 4.13 2.635c.11.16.35.15.44-.025z");
}

.xkw4r_b5w {
  fill: var(--svg-color--f1f1f1, #f1f1f1);
  d: path("M16 4.75c-1 0-2.75 1-3.75 2.5c-1-1.5-2.25-2.5-4.25-2.5c-1.5 0-4 1-4 4.5s6 8 8.25 10c2.25-2 7.75-6.5 7.75-10s-2-4.5-4-4.5");
}

.z4ysap9ca {
  fill: var(--svg-color--fff, #fff);
  d: path("M16 7.25c0-.8-.665-1-1-1c-1.5 0-2 1.9-2 2.25c0 .5.5.5 1 .5s2-.75 2-1.75m-7.215.5c0-.67-.5-1-1-1s-2 .5-2.25 2c-.15.91.215 1.975.62 2.695c.115.2.385.11.405-.12c.135-1.68.78-2.1 1.225-2.325c.5-.25 1-.5 1-1.25");
}

</style>
