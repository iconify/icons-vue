<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="atns_ch0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mtlx" /></template>
<style>
.atns_ch0h {
  fill: var(--svg-color--3e34a7, #3e34a7);
  fill-rule: evenodd;
  d: path("M19.941 4.324H21v14.294h-1.059zM3 4.324h1.059v14.294H3zm3.176 1.588H5.118V17.03h1.058zm11.647 0h1.06v11.647h-1.06zM8.295 6.971h-1.06v11.647h1.06zm7.412-.025h1.059v11.647h-1.06zm-5.294 1.613h-1.06v9h1.06zm3.176 0h1.059v9h-1.059zm-1.058 1.588h-1.06v9.53h1.06z");
}

</style>
