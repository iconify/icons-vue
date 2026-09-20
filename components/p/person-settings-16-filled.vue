<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cbuylycjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-settings-16-filled" /></template>
<style>
.cbuylycjn {
  fill: currentColor;
  d: path("M9.626 5.07a5.5 5.5 0 0 0-3.299 1.847A2.751 2.751 0 1 1 9.626 5.07M5.6 8c-.384.75-.6 1.6-.6 2.5c0 1.31.458 2.512 1.222 3.457C3.555 13.653 2 11.803 2 10v-.5A1.5 1.5 0 0 1 3.5 8zm1.035 1.92a2 2 0 0 0 1.43-2.478l-.156-.557q.383-.293.822-.497l.337.358a2 2 0 0 0 2.91.001l.325-.344q.447.212.834.518l-.126.423a2 2 0 0 0 1.456 2.519l.35.082a4.7 4.7 0 0 1 .01 1.017l-.461.118a2 2 0 0 0-1.43 2.477l.155.557q-.383.294-.822.498l-.337-.358a2 2 0 0 0-2.91-.002l-.324.344a4.3 4.3 0 0 1-.835-.518l.126-.422a2 2 0 0 0-1.456-2.52l-.35-.082a4.7 4.7 0 0 1-.01-1.016zm4.865.58a1 1 0 1 0-2 0a1 1 0 0 0 2 0");
}

</style>
