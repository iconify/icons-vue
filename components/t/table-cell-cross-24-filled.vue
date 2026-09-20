<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m284q-ncl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-cross-24-filled" /></template>
<style>
.m284q-ncl {
  fill: currentColor;
  d: path("M16 19.75A2.25 2.25 0 0 1 13.75 22h-3.5A2.25 2.25 0 0 1 8 19.75V17.5h8zM6.5 16H4.25A2.25 2.25 0 0 1 2 13.75v-3.5A2.25 2.25 0 0 1 4.25 8H6.5zm9.5 0H8V8h8zm3.75-8A2.25 2.25 0 0 1 22 10.25v3.5A2.25 2.25 0 0 1 19.75 16H17.5V8zm-6-6A2.25 2.25 0 0 1 16 4.25V6.5H8V4.25A2.25 2.25 0 0 1 10.25 2z");
}

</style>
