<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-n_6fbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:movie-info-outline-rounded" /></template>
<style>
.o-n_6fbul {
  fill: currentColor;
  d: path("M4.23 20.5q-.69 0-1.152-.462t-.463-1.153V5.115q0-.69.463-1.152T4.231 3.5h15.538q.69 0 1.153.463t.463 1.153v13.769q0 .69-.463 1.153t-1.153.462zm8.127-4.72q.143-.145.143-.357v-4.115q0-.213-.144-.356t-.357-.144t-.356.144t-.143.356v4.115q0 .213.144.356t.357.144t.356-.144M12 9q.262 0 .439-.177q.176-.177.176-.438q0-.262-.177-.439T12 7.77t-.438.177t-.177.439t.177.438T12 9M7.616 19.5h8.769v-15h-8.77zm0-15h8.769zm-3.385 15h2.384v-3h-3v2.385q0 .23.193.423t.423.192m13.154 0h2.384q.231 0 .423-.192t.193-.424V16.5h-3zm-13.77-4h3v-3h-3zm13.77 0h3v-3h-3zm-13.77-4h3v-3h-3zm13.77 0h3v-3h-3zm-13.77-4h3v-3H4.232q-.231 0-.423.192t-.192.423zm13.77 0h3V5.116q0-.231-.193-.424T19.77 4.5h-2.384z");
}

</style>
