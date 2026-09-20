<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxo0dgwor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:transparency-square-24-regular" /></template>
<style>
.qxo0dgwor {
  fill: currentColor;
  d: path("M6.25 3A3.25 3.25 0 0 0 3 6.25v11.5A3.25 3.25 0 0 0 6.25 21h11.5A3.25 3.25 0 0 0 21 17.75V6.25A3.25 3.25 0 0 0 17.75 3zM4.5 6.25c0-.966.784-1.75 1.75-1.75H8V8H4.5zm0 5.75H8V8h4V4.5h4V8h3.5v4H16v4h3.5v1.75a1.75 1.75 0 0 1-1.75 1.75H16V16h-4v3.5H8V16H4.5zm7.5 0V8h4v4zm0 0H8v4h4z");
}

</style>
