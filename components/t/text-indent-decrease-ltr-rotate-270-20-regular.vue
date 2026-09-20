<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1sm5vk4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-decrease-ltr-rotate-270-20-regular" /></template>
<style>
.l1sm5vk4y {
  fill: currentColor;
  d: path("M10 2a.5.5 0 0 1 .5.5v10a.5.5 0 0 1-1 0v-10A.5.5 0 0 1 10 2M6 5.5a.5.5 0 0 0-1 0v7a.5.5 0 0 0 1 0zm9 0a.5.5 0 0 0-1 0v7a.5.5 0 0 0 1 0zm-6.146 9.646a.5.5 0 0 0-.708.708l1.5 1.5a.5.5 0 0 0 .708 0l1.5-1.5a.5.5 0 0 0-.708-.708L10 16.293z");
}

</style>
