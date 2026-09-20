<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p--gu_bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-swap-20-filled" /></template>
<style>
.p--gu_bqk {
  fill: currentColor;
  d: path("M9 2a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-4.991 9A2 2 0 0 0 2 13c0 1.691.833 2.966 2.135 3.797C5.417 17.614 7.145 18 9 18q.431 0 .85-.028l-1.41-1.411a1.5 1.5 0 0 1 0-2.122l2-2A1.5 1.5 0 0 1 12.914 14h1.17a1.5 1.5 0 0 1 1.659-1.98A2 2 0 0 0 14 11zm7.845 6.854a.5.5 0 0 1-.708 0l-2-2a.5.5 0 0 1 0-.708l2-2a.5.5 0 0 1 .708.708L10.707 15h5.586l-1.147-1.146a.5.5 0 0 1 .708-.708l2 2a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708-.708L16.293 16h-5.586l1.147 1.146a.5.5 0 0 1 0 .708");
}

</style>
