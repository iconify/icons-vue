<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fot0jjbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-multiple-24-regular" /></template>
<style>
.fot0jjbcr {
  fill: currentColor;
  d: path("M19.001 6.01a3.25 3.25 0 0 1 3 3.24v8a4.75 4.75 0 0 1-4.75 4.75h-8a3.25 3.25 0 0 1-3.24-3h1.51c.12.848.848 1.5 1.73 1.5h8a3.25 3.25 0 0 0 3.25-3.25v-8c0-.882-.652-1.609-1.5-1.73zM14.75 2A3.25 3.25 0 0 1 18 5.25v9.5A3.25 3.25 0 0 1 14.75 18h-9.5A3.25 3.25 0 0 1 2 14.75v-9.5A3.25 3.25 0 0 1 5.25 2zM3.5 14.75c0 .966.784 1.75 1.75 1.75h9.5a1.75 1.75 0 0 0 1.75-1.75V7.5h-13zM5.25 3.5A1.75 1.75 0 0 0 3.5 5.25V6h13v-.75a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
