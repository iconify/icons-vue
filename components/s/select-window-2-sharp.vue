<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_dgpuhxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:select-window-2-sharp" /></template>
<style>
.w_dgpuhxm {
  fill: currentColor;
  d: path("M20 14.212V6.846H6.77V3H21v11.212zM3 21V9.23h14.616V21z");
}

</style>
