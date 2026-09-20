<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f3ops2dtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-checkmark-16-regular" /></template>
<style>
.f3ops2dtz {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h7a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2zM3 4.5A1.5 1.5 0 0 1 4.5 3h3v4.5H3zm0 4h4.5V13h-3A1.5 1.5 0 0 1 3 11.5zm5.5-1V3h3A1.5 1.5 0 0 1 13 4.5v3zm3.604 2.146a.5.5 0 0 1 0 .708l-1.5 1.5a.5.5 0 0 1-.708 0l-.75-.75a.5.5 0 0 1 .708-.708l.396.397l1.146-1.147a.5.5 0 0 1 .708 0");
}

</style>
