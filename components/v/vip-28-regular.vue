<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="e1afscusx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vip-28-regular" /></template>
<style>
.e1afscusx {
  fill: currentColor;
  d: path("M22.251 4a3.75 3.75 0 0 1 3.75 3.75v12.5a3.75 3.75 0 0 1-3.75 3.75H5.754a3.75 3.75 0 0 1-3.75-3.75V7.75A3.75 3.75 0 0 1 5.754 4zM5.754 5.5a2.25 2.25 0 0 0-2.25 2.25v12.5a2.25 2.25 0 0 0 2.25 2.25H22.25a2.25 2.25 0 0 0 2.25-2.25V7.75a2.25 2.25 0 0 0-2.25-2.25zm5.556 4.958a.75.75 0 1 1 1.38.584l-2.652 6.27a1.128 1.128 0 0 1-2.076 0l-2.652-6.27a.75.75 0 1 1 1.38-.584L9 15.915zM14.75 10a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-1.5 0v-6.5a.75.75 0 0 1 .75-.75m5.5 0a2.75 2.75 0 1 1 0 5.5H19v1.75a.75.75 0 0 1-1.5 0v-6.5a.75.75 0 0 1 .75-.75zM19 14h1.25a1.25 1.25 0 1 0 0-2.5H19z");
}

</style>
