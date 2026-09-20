<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dw90l3f8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sphere-fill" /></template>
<style>
.dw90l3f8q {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m0 16c8.15 0 24 31.06 24 88c0 8.24-.34 15.92-.93 23.07c-7.15.59-14.83.93-23.07.93c-56.94 0-88-15.85-88-24a88.1 88.1 0 0 1 88-88M43.4 152.26C63.28 162.65 95.76 168 128 168c7.09 0 14.19-.26 21.17-.77C144.23 199 134 216 128 216a88.17 88.17 0 0 1-84.6-63.74");
}

</style>
