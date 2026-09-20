<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l9d2__sgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:steam-logo-fill" /></template>
<style>
.l9d2__sgx {
  fill: currentColor;
  d: path("M231.92 132.11c-2.09 54-45.83 97.72-99.81 99.81A104.06 104.06 0 0 1 25.6 109.76a4 4 0 0 1 6.77-2.08l43 43a28 28 0 0 0 42.42 34.92l61.1-49.84a36 36 0 1 0-50.71-50.65l-43 52.74L35 87.67a4 4 0 0 1-.76-4.6a104 104 0 0 1 197.7 49Zm-110.34-13.56l-30.81 37.78a11.83 11.83 0 0 0-2.77 6.86A12.19 12.19 0 0 0 99.85 176a11.84 11.84 0 0 0 7.78-2.74l37.78-30.81a36.18 36.18 0 0 1-23.83-23.9M175.9 110a20 20 0 1 0-17.9 17.9a20 20 0 0 0 17.9-17.9");
}

</style>
