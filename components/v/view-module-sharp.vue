<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f22cqxhyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-module-sharp" /></template>
<style>
.f22cqxhyv {
  fill: currentColor;
  d: path("M15.002 11.616V6h4.979v5.616zm-5.402 0V6h4.825v5.616zm-5.556 0V6h4.979v5.616zm0 6.384v-5.615h4.979V18zM9.6 18v-5.615h4.825V18zm5.402 0v-5.615h4.979V18z");
}

</style>
