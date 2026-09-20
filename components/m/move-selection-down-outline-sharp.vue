<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2og0yb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-selection-down-outline-sharp" /></template>
<style>
.h2og0yb2m {
  fill: currentColor;
  d: path("M6.962 21V10.923h10.077V21zm1-1h8.076v-8.077H7.962zm-1-11.808v-1.23h1.23v1.23zm8.846 0v-1.23h1.23v1.23zM6.962 4.231V3h1.23v1.23zm4.423 0V3h1.23v1.23zm4.423 0V3h1.23v1.23zM12 15.96");
}

</style>
