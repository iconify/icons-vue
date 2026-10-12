<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd-193sau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:plug-puzzle-24-filled" /></template>
<style>
.zd-193sau {
  fill: currentColor;
  d: path("M3 16.35a1 1 0 0 1 1-1h.5a2.25 2.25 0 0 0 2.25-2.25V13a2.25 2.25 0 0 0-2.25-2.25H4a1 1 0 0 1-1-1v-2.5A3.25 3.25 0 0 1 6.25 4H8.5a.75.75 0 1 1 0 1.5H6.25A1.75 1.75 0 0 0 4.5 7.25v2A3.75 3.75 0 0 1 8.25 13v.1a3.75 3.75 0 0 1-3.75 3.75v1.9c0 .966.783 1.75 1.75 1.75h8.5a1.75 1.75 0 0 0 1.75-1.75V15h-.25A4.25 4.25 0 0 1 12 10.75v-3c0-.966.784-1.75 1.75-1.75h.75V4A.75.75 0 0 1 16 4v2h2V4a.75.75 0 0 1 1.5 0v2h.75c.966 0 1.75.784 1.75 1.75v3a4.25 4.25 0 0 1-4 4.242v3.758A3.25 3.25 0 0 1 14.75 22h-8.5A3.25 3.25 0 0 1 3 18.75z");
}

</style>
