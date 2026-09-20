<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru0e3bbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rhombus-24-filled" /></template>
<style>
.ru0e3bbdr {
  fill: currentColor;
  d: path("M5.807 5.408A2.25 2.25 0 0 1 7.894 4h12.858a2.25 2.25 0 0 1 2.087 3.092l-4.642 11.5A2.25 2.25 0 0 1 16.111 20H3.252a2.25 2.25 0 0 1-2.086-3.092z");
}

</style>
