<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ojv1mffei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:remote-20-filled" /></template>
<style>
.ojv1mffei {
  fill: currentColor;
  d: path("M16.97 15.03a.75.75 0 1 0 1.06-1.06L12.56 8.5l5.47-5.47a.75.75 0 0 0-1.06-1.06l-6 6a.75.75 0 0 0 0 1.06zM3.03 4.97a.75.75 0 0 0-1.06 1.06l5.47 5.47l-5.47 5.47a.75.75 0 1 0 1.06 1.06l6-6a.75.75 0 0 0 0-1.06z");
}

</style>
