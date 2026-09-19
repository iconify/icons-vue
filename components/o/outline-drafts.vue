<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u67zmfvlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-drafts" /></template>
<style>
.u67zmfvlq {
  fill: currentColor;
  d: path("M21.99 8c0-.72-.37-1.35-.94-1.7L12 1L2.95 6.3C2.38 6.65 2 7.28 2 8v10c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2zm-2 0v.01L12 13L4 8l8-4.68zM4 18v-7.66l8 5.02l7.99-4.99L20 18z");
}

</style>
