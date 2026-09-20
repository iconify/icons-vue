<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js07chbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-android-outline-sharp" /></template>
<style>
.js07chbey {
  fill: currentColor;
  d: path("M10.23 19.654h3.54v-.77h-3.54zM6 22V2h12v20zm1-4.461V21h10v-3.462zm0-1h10V5.5H7zM7 4.5h10V3H7zm0 13.039V21zM7 4.5V3z");
}

</style>
