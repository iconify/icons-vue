<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6t72_b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:power-24-filled" /></template>
<style>
.z6t72_b3f {
  fill: currentColor;
  d: path("M8.205 4.843a1 1 0 0 1 .844 1.813A6.997 6.997 0 0 0 12 20a6.998 6.998 0 0 0 2.965-13.337a1 1 0 0 1 .848-1.811A9 9 0 0 1 21 13.003C21 17.972 16.97 22 12 22s-9-4.028-9-8.997a9 9 0 0 1 5.205-8.16M12 2a1 1 0 0 1 .993.883L13 3v7a1 1 0 0 1-1.993.117L11 10V3a1 1 0 0 1 1-1");
}

</style>
