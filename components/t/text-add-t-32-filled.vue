<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x8dbmmbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-add-t-32-filled" /></template>
<style>
.x8dbmmbsp {
  fill: currentColor;
  d: path("M23 15.5a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15M22.75 4c.69 0 1.25.56 1.25 1.25v3.5a1.25 1.25 0 1 1-2.5 0V6.5h-6.25v11.924A8.96 8.96 0 0 0 14 23c0 1.85.56 3.57 1.517 5H11.25a1.25 1.25 0 1 1 0-2.5h1.5v-19H6.5v2.25a1.25 1.25 0 1 1-2.5 0v-3.5C4 4.56 4.56 4 5.25 4zm.5 13.5a.75.75 0 0 0-.75.75V22h-3.75a.75.75 0 0 0 0 1.5h3.75v3.75a.75.75 0 0 0 1.5 0V23.5h3.75a.75.75 0 0 0 0-1.5H24v-3.75a.75.75 0 0 0-.75-.75");
}

</style>
