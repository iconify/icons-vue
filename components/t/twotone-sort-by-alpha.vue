<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd-21ri8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sort-by-alpha" /></template>
<style>
.bd-21ri8r {
  fill: currentColor;
  d: path("M14.94 4.66L12.58 2.3l-2.36 2.36zm-4.55 13.07h1.84L7.74 6.27H6.1L1.6 17.73h1.84l.92-2.45h5.11zm-5.42-4.09l1.94-5.18l1.94 5.18zm7.61 8.06l2.33-2.33h-4.66zm9.08-14.16V6.28h-8.3v1.6h5.88l-5.92 8.56v1.29h8.53v-1.59h-6.12z");
}

</style>
