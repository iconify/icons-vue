<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwq3fki6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xchf" /></template>
<style>
.pwq3fki6v {
  fill: var(--svg-color--ce0e2d, #ce0e2d);
  d: path("m8.75 13.07l-.497-.812L5.628 16.5h1.59L13.668 6L21 18h-9.239l-1.54-2.522l.873-1.426l1.528 2.448h5.75l-4.703-7.644L8.079 18H3l5.253-8.594l1.369 2.237z");
}

</style>
