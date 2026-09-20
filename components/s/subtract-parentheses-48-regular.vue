<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ri5kssbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtract-parentheses-48-regular" /></template>
<style>
.ri5kssbvg {
  fill: currentColor;
  d: path("M13.499 10a1.25 1.25 0 1 0-1.502-2C7.143 11.648 4 17.458 4 24s3.143 12.353 7.997 16a1.25 1.25 0 1 0 1.502-2C9.247 34.807 6.5 29.725 6.5 24s2.747-10.806 6.999-14m22.504-2a1.25 1.25 0 1 0-1.502 2c4.252 3.194 6.999 8.276 6.999 14s-2.747 10.806-6.999 14a1.25 1.25 0 0 0 1.502 2C40.856 36.352 44 30.542 44 24s-3.144-12.353-7.997-16M15.25 22.75a1.25 1.25 0 0 0 0 2.5h17.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
