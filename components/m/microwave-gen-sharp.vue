<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_tyij_ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:microwave-gen-sharp" /></template>
<style>
.w_tyij_ic {
  fill: currentColor;
  d: path("M3 19V5h18v14zm2.885-2.884h8.23V7.885h-8.23zm1-1V8.885h6.23v6.23zm9.961-5.693h1.539V7.885h-1.539zm0 3.346h1.539v-1.538h-1.539zm0 3.347h1.539v-1.539h-1.539z");
}

</style>
