<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5gulm5ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:projection-screen-24-regular" /></template>
<style>
.e5gulm5ct {
  fill: currentColor;
  d: path("M3.5 3A1.5 1.5 0 0 0 3 5.915v7.335A3.75 3.75 0 0 0 6.75 17h4.5v2.5h-3.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5h-3.5V17h4.5A3.75 3.75 0 0 0 21 13.25V5.915A1.5 1.5 0 0 0 20.5 3zm1 3h15v7.25a2.25 2.25 0 0 1-2.25 2.25H6.75a2.25 2.25 0 0 1-2.25-2.25z");
}

</style>
