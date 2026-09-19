<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwo9mmu7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-browser-updated" /></template>
<style>
.kwo9mmu7l {
  fill: currentColor;
  d: path("M22 13v5h-5l1 1v2H6v-2l1-1H2V3h10v2H4v11h16v-3zm-7 2l-5-5h4V3h2v7h4z");
}

</style>
