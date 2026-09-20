<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh-usac0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:privacy-screen-outline" /></template>
<style>
.qh-usac0l {
  fill: currentColor;
  d: path("M4 9.6L7.6 6H4v3.6Zm0 7L14.575 6H10.4L4 12.425V16.6ZM5.4 18H20V6h-2.6l-12 12ZM4 20q-.825 0-1.413-.588T2 18V6q0-.825.588-1.413T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.588 1.413T20 20H4Z");
}

</style>
