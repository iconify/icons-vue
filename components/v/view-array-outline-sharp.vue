<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z47rdsbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-array-outline-sharp" /></template>
<style>
.z47rdsbff {
  fill: currentColor;
  d: path("M4 18V6h2.346v12zm3.73 0V6h8.54v12zm9.924 0V6H20v12zM8.73 17h6.538V7H8.731zM12 12");
}

</style>
