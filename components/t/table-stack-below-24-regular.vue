<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-0xcbbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-stack-below-24-regular" /></template>
<style>
.c-0xcbbjo {
  fill: currentColor;
  d: path("M3.75 15.5a.75.75 0 0 1-.75-.75v-8.5A3.25 3.25 0 0 1 6.25 3h11.5A3.25 3.25 0 0 1 21 6.25v8.5a.75.75 0 0 1-.75.75zM10 14h4v-4h-4zm0-5.5h4v-4h-4zm5.5 5.5h4v-4h-4zm0-5.5h4V6.25a1.75 1.75 0 0 0-1.75-1.75H15.5zm-7-4H6.25A1.75 1.75 0 0 0 4.5 6.25V8.5h4zm-4 9.5h4v-4h-4zm-.75 5.5a.75.75 0 0 0 0 1.5h16.5a.75.75 0 0 0 0-1.5z");
}

</style>
