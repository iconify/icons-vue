<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_wbdz4ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:poll-horizontal-24-filled" /></template>
<style>
.m_wbdz4ce {
  fill: currentColor;
  d: path("M22 11.752a2.75 2.75 0 0 1-2.751 2.752h-14.5A2.752 2.752 0 1 1 4.75 9h14.5A2.75 2.75 0 0 1 22 11.752m-5 7a2.75 2.75 0 0 1-2.751 2.752h-9.5a2.752 2.752 0 1 1 0-5.504h9.5A2.75 2.75 0 0 1 17 18.752m-5-14a2.75 2.75 0 0 1-2.752 2.752H4.75A2.752 2.752 0 1 1 4.75 2h4.498A2.75 2.75 0 0 1 12 4.752");
}

</style>
