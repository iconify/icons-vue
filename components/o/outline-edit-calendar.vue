<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t36fusbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-edit-calendar" /></template>
<style>
.t36fusbcf {
  fill: currentColor;
  d: path("M5 10h14v2h2V6c0-1.1-.9-2-2-2h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20a2 2 0 0 0 2 2h7v-2H5zm0-4h14v2H5zm17.84 10.28l-.71.71l-2.12-2.12l.71-.71a.996.996 0 0 1 1.41 0l.71.71c.39.39.39 1.02 0 1.41m-3.54-.7l2.12 2.12l-5.3 5.3H14v-2.12z");
}

</style>
