<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e7xyfkb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-12-filled" /></template>
<style>
.e7xyfkb6l {
  fill: currentColor;
  d: path("M11 6A5 5 0 1 1 1 6a5 5 0 0 1 10 0m-6.783.264A.84.84 0 0 0 4 6.81v.16c0 .817.817 1.53 2 1.53s2-.713 2-1.53v-.16a.84.84 0 0 0-.217-.546A.75.75 0 0 0 7.225 6h-2.45a.75.75 0 0 0-.558.264M6 5a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
