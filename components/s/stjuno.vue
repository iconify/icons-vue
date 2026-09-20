<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gdzdahbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stjuno" /></template>
<style>
.gdzdahbhb {
  fill: var(--svg-color--e40570, #e40570);
  fill-rule: evenodd;
  d: path("M21 12a9 9 0 1 1-18 0a9 9 0 0 1 18 0m-.582 0a8.418 8.418 0 1 1-16.836 0a8.418 8.418 0 0 1 16.836 0m-8.947 4.765v1.058h1.059v-1.058h1.588v-1.06H12.53v-3.97l1.852 1.853l.795-.794l-1.854-1.853h2.383V9.882h-2.383l1.854-1.853l-.795-.794l-1.852 1.853V6.706h-1.06v2.382L9.619 7.235l-.794.794l1.853 1.853H8.294v1.06h2.383l-1.853 1.852l.794.794l1.852-1.853v3.97H9.883v1.06z");
}

</style>
