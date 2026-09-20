<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGeA3FUdUn)" class="t_f6cnb_z"/><path fill="url(#SVGwvdoEcBd)" class="vir4ma65k"/><defs><linearGradient id="SVGeA3FUdUn" x1="12" x2="12" y1="3" y2="20.998" gradientUnits="userSpaceOnUse"><stop class="bn2eh8yok"/><stop offset="1" class="zaoyf_b2t"/></linearGradient><linearGradient id="SVGwvdoEcBd" x1="11.5" x2="11.5" y1="9.499" y2="14.499" gradientUnits="userSpaceOnUse"><stop class="bn2eh8yok"/><stop offset="1" class="zaoyf_b2t"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:moov" /></template>
<style>
.bn2eh8yok {
  stop-color: var(--svg-color--ff825f, #ff825f);
}

.ft5dv1b6b {
  fill: none;
}

.t_f6cnb_z {
  d: path("m9.75 3.09l9.67 5.7c.2.12.33.34.33.58v5.28a.67.67 0 0 1-.33.579l-9.665 5.68a.65.65 0 0 1-.665 0l-4.515-2.72a.68.68 0 0 1-.325-.58v-11.3c0-.24.125-.46.33-.58L9.095 3.09c.2-.12.45-.12.655 0m-3 1.99v13.814c0 .2.22.33.395.23l11.974-6.93a.265.265 0 0 0 0-.455L7.14 4.85a.26.26 0 0 0-.39.23");
}

.vir4ma65k {
  d: path("M9.25 13.824v-3.65a.67.67 0 0 1 1-.585l3.164 1.82c.45.26.45.91 0 1.17l-3.16 1.83a.67.67 0 0 1-1.004-.586");
}

.zaoyf_b2t {
  stop-color: var(--svg-color--ff3e68, #ff3e68);
}

</style>
