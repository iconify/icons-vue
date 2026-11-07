<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5u4-wb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mirror-stack-outline-sharp" /></template>
<style>
.w5u4-wb8u {
  fill: currentColor;
  d: path("M13.423 17.23v-1H18V4h-6.423v3.039h-1V3H19v14.23zM6 20h6.423V7.789H6zm-1 1V6.789h8.423V21zm1-1V7.789zM18 4.596V4v12.23z");
}

</style>
