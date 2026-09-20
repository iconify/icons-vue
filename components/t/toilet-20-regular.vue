<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xviajwblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toilet-20-regular" /></template>
<style>
.xviajwblq {
  fill: currentColor;
  d: path("M16.5 1A1.5 1.5 0 0 1 18 2.5v6a2.5 2.5 0 0 1-1.999 2.45V16a2 2 0 0 1-2 2h-8a1 1 0 0 1-.908-1.419l1.289-2.797A6 6 0 0 1 4.05 9.76A1.999 1.999 0 0 1 5 6h8V2.5A1.5 1.5 0 0 1 14.5 1zm-1.499 11.313a5.99 5.99 0 0 1-5 2.687a6 6 0 0 1-2.767-.676L6.001 17h8a1 1 0 0 0 1-1zM13.5 10H5.102a5.001 5.001 0 0 0 9.546.848a2.5 2.5 0 0 1-1.145-.849zm1-8a.5.5 0 0 0-.5.5v6a1.5 1.5 0 0 0 3 0v-6a.5.5 0 0 0-.5-.5zM5 7a1 1 0 0 0 0 2h8.05a2.5 2.5 0 0 1-.05-.5V7z");
}

</style>
