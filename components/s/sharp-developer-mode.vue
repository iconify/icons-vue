<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c83cblb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-developer-mode" /></template>
<style>
.c83cblb0v {
  fill: currentColor;
  d: path("M7 5h10v2h2V1.01L5 1v6h2zm8.41 11.59L20 12l-4.59-4.59L14 8.83L17.17 12L14 15.17zM10 15.17L6.83 12L10 8.83L8.59 7.41L4 12l4.59 4.59zM17 19H7v-2H5v6h14v-6h-2z");
}

</style>
