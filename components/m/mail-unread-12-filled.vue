<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tw3akabhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-unread-12-filled" /></template>
<style>
.tw3akabhl {
  fill: currentColor;
  d: path("M9.5 4.5a1 1 0 1 0 0-2a1 1 0 0 0 0 2M3.5 3h4.063a2 2 0 0 0 .593 1.981L6 5.951L2.037 4.169A1.5 1.5 0 0 1 3.5 3m2.705 3.956l3.237-1.457A2 2 0 0 0 10 5.437V7.5A1.5 1.5 0 0 1 8.5 9h-5A1.5 1.5 0 0 1 2 7.5V5.248l3.794 1.708a.5.5 0 0 0 .41 0");
}

</style>
