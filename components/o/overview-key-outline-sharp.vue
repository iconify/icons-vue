<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkj2ekbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:overview-key-outline-sharp" /></template>
<style>
.lkj2ekbhp {
  fill: currentColor;
  d: path("M1.77 18V6h12v12zm1-1h10V7h-10zM17 18V6h1v12zm4.23 0V6h1v12zM2.77 17V7z");
}

</style>
