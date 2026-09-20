<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0vsvgbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-comfy-sharp" /></template>
<style>
.o0vsvgbcl {
  fill: currentColor;
  d: path("M2 11V4h20v7zm8 9v-7h12v7zm-8 0v-7h6v7z");
}

</style>
