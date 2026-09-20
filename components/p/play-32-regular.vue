<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j2utntbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:play-32-regular" /></template>
<style>
.j2utntbof {
  fill: currentColor;
  d: path("M11.24 6.203A1.5 1.5 0 0 0 9 7.508V24.5a1.5 1.5 0 0 0 2.24 1.305l14.997-8.498a1.5 1.5 0 0 0 0-2.61zM7 7.508c0-2.681 2.891-4.367 5.225-3.046l14.997 8.493c2.367 1.34 2.368 4.75.001 6.09l-14.997 8.5C9.892 28.865 7 27.18 7 24.498z");
}

</style>
