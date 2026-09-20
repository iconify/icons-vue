<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d4-ofirmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-moon-off-16-regular" /></template>
<style>
.d4-ofirmy {
  fill: currentColor;
  d: path("M1.147 1.146a.5.5 0 0 1 .707 0l13 13a.5.5 0 1 1-.707.707l-1.565-1.564A6.97 6.97 0 0 1 8.002 15a7 7 0 0 1-6.464-4.309a.5.5 0 0 1 .474-.692a5.99 5.99 0 0 0 4.826-2.454L1.147 1.854a.5.5 0 0 1 0-.708M7.552 8.26a7 7 0 0 1-4.772 2.696a5.997 5.997 0 0 0 9.093 1.625zM8.003 1a7 7 0 0 1 5.893 10.774l-.727-.726a6 6 0 0 0-4.447-9.004a7 7 0 0 1-.16 4.397l-.792-.793a6 6 0 0 0-.229-3.956A.5.5 0 0 1 8.003 1");
}

</style>
