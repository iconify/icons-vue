<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o293l4bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shield-prohibited-24-filled" /></template>
<style>
.o293l4bob {
  fill: currentColor;
  d: path("M3.75 5a.75.75 0 0 0-.75.75V11c0 5.001 2.958 8.676 8.725 10.948a.75.75 0 0 0 .55 0q.216-.085.426-.173a6.5 6.5 0 1 1 8.274-9.99Q21 11.399 21 11V5.75a.75.75 0 0 0-.75-.75c-2.663 0-5.258-.943-7.8-2.85a.75.75 0 0 0-.9 0C9.008 4.057 6.413 5 3.75 5M16.5 22a5.5 5.5 0 1 0 0-11a5.5 5.5 0 0 0 0 11m-3.309-3.252a4 4 0 0 1 5.557-5.557zm1.06 1.06l5.558-5.556a4 4 0 0 1-5.557 5.557");
}

</style>
