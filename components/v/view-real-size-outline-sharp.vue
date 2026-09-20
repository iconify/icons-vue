<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qetmcvbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-real-size-outline-sharp" /></template>
<style>
.qetmcvbut {
  fill: currentColor;
  d: path("M7.827 16V9H6V8h2.827v8zm3.635 0v-1h1v1zM16 16V9h-1.808V8H17v8zm-4.538-3.5v-1h1v1z");
}

</style>
