<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f064b0b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:serial-port-off-24-filled" /></template>
<style>
.f064b0b3n {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-4.78-4.779H5.98a2.75 2.75 0 0 1-2.675-2.113l-1.072-4.501a2.75 2.75 0 0 1 2.675-3.388h1.031L2.22 3.28a.75.75 0 0 1 0-1.06m16.872 4.779a2.75 2.75 0 0 1 2.675 3.389l-1.075 4.502a2.74 2.74 0 0 1-1.047 1.574l-4.982-4.983a.75.75 0 1 0-.894-.894L10.18 6.999zM8.25 12.5a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m2.5 0a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M7 10a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m2.073.134a.749.749 0 1 0 1.042 1.042zM17 10a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>
