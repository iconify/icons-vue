<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGKSmJTI6E)" class="cfgx_8blx"/><defs><linearGradient id="SVGKSmJTI6E" x1="8.304" x2="15.388" y1="4.467" y2="20.044" gradientUnits="userSpaceOnUse"><stop class="xabpkybjo"/><stop offset=".38" class="z4r7ovg-y"/><stop offset=".73" class="l73tyqb3g"/><stop offset="1" class="l01fejbda"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rev3l" /></template>
<style>
.cfgx_8blx {
  d: path("M15.937 3.563L14.25 6.374H8.248c-.872 0-2.435.664-2.435 2.812c0 2.15 1.653 2.684 2.53 2.813h2.813l-4.219 8.438H3.281l3.094-6.188C5.25 13.867 3 12.872 3 9.187s3.375-5.624 5.062-5.624zM8.062 20.438l1.407-2.813h6.283c.872 0 2.435-.664 2.435-2.812c0-2.15-1.653-2.684-2.53-2.813h-3.094l4.5-8.437h3.656l-3.094 6.13c1.125.395 3.375 1.435 3.375 5.12s-2.813 5.624-5.063 5.624z");
}

.ft5dv1b6b {
  fill: none;
}

.l01fejbda {
  stop-color: var(--svg-color--c56058, #c56058);
}

.l73tyqb3g {
  stop-color: var(--svg-color--622065, #622065);
}

.xabpkybjo {
  stop-color: var(--svg-color--242a3f, #242a3f);
}

.z4r7ovg-y {
  stop-color: var(--svg-color--321b65, #321b65);
}

</style>
