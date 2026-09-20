<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jdsgg5bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-decrease-rtl-rotate-270-20-regular" /></template>
<style>
.jdsgg5bpc {
  fill: currentColor;
  d: path("M11.146 4.854a.5.5 0 0 0 .708-.708l-1.5-1.5a.5.5 0 0 0-.708 0l-1.5 1.5a.5.5 0 1 0 .708.708L10 3.707zM6 7.5a.5.5 0 0 0-1 0v7a.5.5 0 0 0 1 0zm9 0a.5.5 0 0 0-1 0v7a.5.5 0 0 0 1 0zm-5.5 0a.5.5 0 0 1 1 0v10a.5.5 0 0 1-1 0z");
}

</style>
