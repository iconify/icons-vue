<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="ov45av1-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-unknown-10-regular" /></template>
<style>
.ov45av1-f {
  fill: currentColor;
  d: path("M4.999 1a3.999 3.999 0 1 0 0 7.997a3.999 3.999 0 0 0 0-7.997M0 4.999a4.999 4.999 0 1 1 9.997 0a4.999 4.999 0 0 1-9.997 0");
}

</style>
