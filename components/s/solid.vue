<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG126ORcgW)" class="vb7n012lj"/><defs><linearGradient id="SVG126ORcgW" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="dltdc5rjj"/><stop offset="1" class="oakdr_dxm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:solid" /></template>
<style>
.dltdc5rjj {
  stop-color: var(--svg-color--00c0d6, #00c0d6);
}

.ft5dv1b6b {
  fill: none;
}

.oakdr_dxm {
  stop-color: var(--svg-color--10f9db, #10f9db);
}

.vb7n012lj {
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

</style>
