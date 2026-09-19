<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxnuqfg0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-tune" /></template>
<style>
.cxnuqfg0z {
  fill: currentColor;
  d: path("M3 5h10v2H3zm4 6H3v2h4v2h2V9H7zm6 4h-2v6h2v-2h8v-2h-8zM3 17h6v2H3zm8-6h10v2H11zm6-8h-2v6h2V7h4V5h-4z");
}

</style>
