<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm16k9uov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-mobile-24-filled" /></template>
<style>
.wm16k9uov {
  d: path("M15.75 2A2.25 2.25 0 0 1 18 4.25v15.5A2.25 2.25 0 0 1 15.75 22h-7.5A2.25 2.25 0 0 1 6 19.75V4.25A2.25 2.25 0 0 1 8.25 2h7.5zm-2.5 16h-2.5a.75.75 0 1 0 0 1.5h2.5a.75.75 0 1 0 0-1.5z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>
