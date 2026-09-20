<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p57kn7xer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-list-roman-numeral-lowercase-24-regular" /></template>
<style>
.p57kn7xer {
  fill: currentColor;
  d: path("M5.25 3.5a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5M6 4.75a.75.75 0 0 0-1.5 0v2.5a.75.75 0 0 0 1.5 0zM5.25 11a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 .75-.75m0 7a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 .75-.75M9 5.75A.75.75 0 0 1 9.75 5h9.5a.75.75 0 0 1 0 1.5h-9.5A.75.75 0 0 1 9 5.75m0 6.5a.75.75 0 0 1 .75-.75h9.5a.75.75 0 0 1 0 1.5h-9.5a.75.75 0 0 1-.75-.75m0 6.5a.75.75 0 0 1 .75-.75h9.5a.75.75 0 0 1 0 1.5h-9.5a.75.75 0 0 1-.75-.75M5.25 17.5a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5M6 9.75a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

</style>
