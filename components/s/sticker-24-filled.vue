<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2k6d0_bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sticker-24-filled" /></template>
<style>
.f2k6d0_bn {
  fill: currentColor;
  d: path("M17.75 3A3.25 3.25 0 0 1 21 6.25v6.749L16.251 13l-.213.007a3.25 3.25 0 0 0-2.714 1.832q-.63.17-1.323.17a4.84 4.84 0 0 1-2.824-.873a.75.75 0 1 0-.854 1.233a6.34 6.34 0 0 0 3.678 1.14q.34 0 .671-.032l.329-.04L13 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zm2.591 11.72l-5.621 5.62a2 2 0 0 1-.218.191L14.5 16.25l.006-.143a1.75 1.75 0 0 1 1.593-1.6l.151-.007h4.282q-.089.115-.192.22M9.001 7.75a1.25 1.25 0 1 0 0 2.499A1.25 1.25 0 0 0 9 7.75m6 0a1.25 1.25 0 1 0 0 2.499a1.25 1.25 0 0 0 0-2.499");
}

</style>
