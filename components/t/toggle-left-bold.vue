<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqqoj9xsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:toggle-left-bold" /></template>
<style>
.vqqoj9xsq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 6C19.3137 6 22 8.6863 22 12C22 15.3137 19.3137 18 16 18H8C4.6863 18 2 15.3137 2 12C2 8.6863 4.6863 6 8 6H16ZM8 9C6.3431 9 5 10.3431 5 12C5 13.6569 6.3431 15 8 15C9.6569 15 11 13.6569 11 12C11 10.3431 9.6569 9 8 9Z");
}

</style>
