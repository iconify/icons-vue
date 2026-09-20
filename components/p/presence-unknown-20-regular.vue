<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x3p_2cbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-unknown-20-regular" /></template>
<style>
.x3p_2cbwe {
  fill: currentColor;
  d: path("M9.997 2a7.997 7.997 0 1 0 0 15.995A7.997 7.997 0 0 0 9.997 2M0 9.997C0 4.476 4.476 0 9.997 0c5.522 0 9.998 4.476 9.998 9.997c0 5.522-4.476 9.998-9.998 9.998S0 15.519 0 9.997");
}

</style>
