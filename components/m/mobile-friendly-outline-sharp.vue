<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il5h1_uxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-friendly-outline-sharp" /></template>
<style>
.il5h1_uxn {
  fill: currentColor;
  d: path("M5 22V2h12v4.923h-1V5.5H6v13h10v-1.423h1V22zm1-2.5V21h10v-1.5zm0-15h10V3H6zm0 0V3zm0 15V21zm8.95-4.192l-3.558-3.558l.708-.708l2.85 2.85l5.689-5.688l.707.707z");
}

</style>
