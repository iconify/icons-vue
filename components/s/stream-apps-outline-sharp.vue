<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-y9a4bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stream-apps-outline-sharp" /></template>
<style>
.r-y9a4bwi {
  fill: currentColor;
  d: path("M15.116 13.692h5.653v-4h-5.653zm-1 2.481v-7.48h7.653v6h-6.173zM6 22V2h12v4.923h-1V5.5H7v13h10v-1.423h1V22zm1-2.5V21h10v-1.5zm0-15h10V3H7zm0 0V3zm0 15V21zm8.116-5.808v-4z");
}

</style>
