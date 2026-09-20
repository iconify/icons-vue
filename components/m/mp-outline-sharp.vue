<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3_sh_egb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mp-outline-sharp" /></template>
<style>
.n3_sh_egb {
  fill: currentColor;
  d: path("M6.308 14.692h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V9.308H6.308zm7.5 0h.884v-1.5h3V9.308h-3.884zm.884-2.384v-2.116h2.116v2.116zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
