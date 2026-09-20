<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jv7cd662t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-multiple-16-filled" /></template>
<style>
.jv7cd662t {
  fill: currentColor;
  d: path("M3.818 3.818a4.5 4.5 0 0 1 5.79-.486L3.332 9.608a4.5 4.5 0 0 1 .486-5.79m.574 6.85l6.276-6.276a4.501 4.501 0 0 1-6.276 6.276m6.85-7.91a6 6 0 1 0-8.485 8.485a6 6 0 0 0 8.486-8.486M14 7a7 7 0 0 1-8.394 6.861a6 6 0 0 0 8.256-8.255Q13.997 6.283 14 7");
}

</style>
