<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1h0hhzfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mtd" /></template>
<style>
.s1h0hhzfp {
  fill: var(--svg-color--ff1826, #ff1826);
  d: path("M3 16.5h13.5V3H21v18H3zM3 3h4.5v7.072H3zm6.429 0h4.5v7.072h-4.5z");
}

</style>
