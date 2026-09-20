<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="svi17vb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-32-filled" /></template>
<style>
.svi17vb1e {
  fill: currentColor;
  d: path("M23.5 2A4.5 4.5 0 0 1 28 6.5v19a4.5 4.5 0 0 1-4.5 4.5h-15a4.5 4.5 0 0 1-4.494-4.269L4 25.5v-19A4.5 4.5 0 0 1 8.5 2zm-8.472 9.288c-1.333-.8-3.028.16-3.028 1.715v5.994c0 1.555 1.695 2.514 3.028 1.715l4.998-2.997c1.295-.777 1.295-2.653 0-3.43z");
}

</style>
