<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":257};
const content = `<path class="pvwin0bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:rax" /></template>
<style>
.pvwin0bck {
  fill: var(--svg-color--f76927, #f76927);
  d: path("m.61.667l62.848 64.059l103.504-.764s23.118 1.788 23.118 30.211c0 28.424-19.61 30.47-19.61 30.47l-42.732 1.146l58.56 61.224S256 171.199 256 94.413S176.607 0 176.607 0zM0 126.313h89.65l127.598 128.36l-90.652 1.76z");
}

</style>
