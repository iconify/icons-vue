<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxoy4l3bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:orders-outline" /></template>
<style>
.pxoy4l3bk {
  fill: currentColor;
  d: path("M4 20V7.1L2.05 2.85L3.85 2L6.2 7.05h11.6L20.15 2l1.8.85L20 7.1V20zm6-7h4q.425 0 .713-.288T15 12t-.288-.712T14 11h-4q-.425 0-.712.288T9 12t.288.713T10 13m-4 5h12V9.05H6zm0 0V9.05z");
}

</style>
