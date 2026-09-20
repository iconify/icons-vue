<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ke59q6-zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-increase-rtl-rotate-270-20-regular" /></template>
<style>
.ke59q6-zs {
  fill: currentColor;
  d: path("M8.854 2.646a.5.5 0 1 0-.708.708l1.5 1.5a.5.5 0 0 0 .708 0l1.5-1.5a.5.5 0 0 0-.708-.708L10 3.793zM6 7.5a.5.5 0 0 0-1 0v7a.5.5 0 0 0 1 0zm9 0a.5.5 0 0 0-1 0v7a.5.5 0 0 0 1 0zm-5.5 10v-10a.5.5 0 0 1 1 0v10a.5.5 0 0 1-1 0");
}

</style>
