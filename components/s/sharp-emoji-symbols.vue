<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sra6dpe_q"/><circle class="y2d76qgdf"/><circle class="w01xx4bie"/><path class="xr1r4f-vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-emoji-symbols" /></template>
<style>
.sra6dpe_q {
  fill: currentColor;
  d: path("M3 2h8v2H3zm3 9h2V7h3V5H3v2h3zm6.404 9.182l7.778-7.778l1.414 1.414l-7.778 7.778z");
}

.w01xx4bie {
  cx: 19.5px;
  cy: 19.5px;
  r: 1.5px;
  fill: currentColor;
}

.xr1r4f-vg {
  fill: currentColor;
  d: path("M15.5 11A2.5 2.5 0 0 0 18 8.5V4h3V2h-4v4.51c-.42-.32-.93-.51-1.5-.51a2.5 2.5 0 0 0 0 5m-5.76 4.96l-1.41 1.41l-.71-.71l.35-.35a2.499 2.499 0 0 0-1.77-4.27a2.499 2.499 0 0 0-1.77 4.27l.35.35l-1.06 1.06c-.98.98-.98 2.56 0 3.54c.5.5 1.14.74 1.78.74s1.28-.24 1.77-.73l1.06-1.06l1.41 1.41l1.41-1.41l-1.41-1.41l1.41-1.41zM5.85 14.2c.12-.12.26-.15.35-.15s.23.03.35.15c.19.2.19.51 0 .71l-.35.35l-.35-.36a.5.5 0 0 1 0-.7m0 5.65c-.12.12-.26.15-.35.15s-.23-.03-.35-.15a.513.513 0 0 1 0-.71l1.06-1.06l.71.71z");
}

.y2d76qgdf {
  cx: 14.5px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
