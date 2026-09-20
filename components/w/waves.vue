<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sycvawb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:waves" /></template>
<style>
.sycvawb1d {
  fill: var(--svg-color--1857f5, #1857f5);
  d: path("m3 12l9-9l9 9l-9 9z");
}

</style>
