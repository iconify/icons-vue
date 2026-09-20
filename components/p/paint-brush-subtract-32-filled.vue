<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j4misj8rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:paint-brush-subtract-32-filled" /></template>
<style>
.j4misj8rp {
  fill: currentColor;
  d: path("M17 2v5a1 1 0 1 0 2 0V2h2v7a1 1 0 1 0 2 0V2h2a1 1 0 0 1 1 1v11H6V3a1 1 0 0 1 1-1zm-3 21a8.98 8.98 0 0 1 3.343-7H6v2.75A3.25 3.25 0 0 0 9.25 22H12v4a4 4 0 0 0 5.144 3.834A8.98 8.98 0 0 1 14 23m16.5 0a7.5 7.5 0 1 1-15 0a7.5 7.5 0 0 1 15 0M18 22.75c0 .414.336.75.75.75h8.5a.75.75 0 0 0 0-1.5h-8.5a.75.75 0 0 0-.75.75");
}

</style>
