<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjy_rrvaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-cross-24-regular" /></template>
<style>
.sjy_rrvaf {
  fill: currentColor;
  d: path("M13.75 2A2.25 2.25 0 0 1 16 4.25V8h3.75A2.25 2.25 0 0 1 22 10.25v3.5A2.25 2.25 0 0 1 19.75 16H16v3.75A2.25 2.25 0 0 1 13.75 22h-3.5A2.25 2.25 0 0 1 8 19.75V16H4.25A2.25 2.25 0 0 1 2 13.75v-3.5A2.25 2.25 0 0 1 4.25 8H8V4.25A2.25 2.25 0 0 1 10.25 2zM9.5 19.75c0 .414.336.75.75.75h3.5a.75.75 0 0 0 .75-.75V16h-5zM4.25 9.5a.75.75 0 0 0-.75.75v3.5c0 .414.336.75.75.75H8v-5zm5.25 5h5v-5h-5zm6.5 0h3.75a.75.75 0 0 0 .75-.75v-3.5a.75.75 0 0 0-.75-.75H16zm-5.75-11a.75.75 0 0 0-.75.75V8h5V4.25a.75.75 0 0 0-.75-.75z");
}

</style>
