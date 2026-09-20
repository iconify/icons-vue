<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu3e3bbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thumbnail-bar-outline-sharp" /></template>
<style>
.bu3e3bbkv {
  fill: currentColor;
  d: path("M2 20V4h20v16zm8-2h10V6H10zm-2 0V6H4v12zm-4 0V6zm4 0h2zM8 6h2z");
}

</style>
