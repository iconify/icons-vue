<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x58lx5hsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-mail-16-filled" /></template>
<style>
.x58lx5hsw {
  fill: currentColor;
  d: path("M2 10c0 1.507 1.086 3.047 3 3.69V9c0-.364.097-.706.268-1H3.5A1.5 1.5 0 0 0 2 9.5zm5-8.5A2.75 2.75 0 1 1 7 7a2.75 2.75 0 0 1 0-5.5m3.51 10.427L6.013 9.304A1.5 1.5 0 0 1 7.5 8h6A1.5 1.5 0 0 1 15 9.5v.01zm.227 1.013L15 10.645V13.5a1.5 1.5 0 0 1-1.5 1.5h-6A1.5 1.5 0 0 1 6 13.5v-3.046l4.248 2.478a.5.5 0 0 0 .49.008");
}

</style>
