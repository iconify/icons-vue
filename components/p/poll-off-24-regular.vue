<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emnazy3as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:poll-off-24-regular" /></template>
<style>
.emnazy3as {
  fill: currentColor;
  d: path("M9 10.06L2.22 3.28a.75.75 0 1 1 1.06-1.06l18.5 18.5a.75.75 0 0 1-1.06 1.06l-.324-.323A2.752 2.752 0 0 1 16 19.25v-2.19l-1.496-1.495v3.685a2.752 2.752 0 1 1-5.504 0zm4.004 4.005L10.5 11.56v7.689a1.252 1.252 0 0 0 2.504 0zM17.5 18.56v.689a1.252 1.252 0 0 0 1.81 1.12zM13.004 4.75v5.07l1.5 1.5V4.75A2.752 2.752 0 1 0 9 4.75v1.067l1.5 1.5V4.751a1.252 1.252 0 0 1 2.504 0M16 12.818l1.5 1.5V9.751a1.252 1.252 0 0 1 2.504 0v7.071l1.5 1.5v-8.57a2.752 2.752 0 1 0-5.504 0zM4.752 12a2.75 2.75 0 0 1 2.752 2.752v4.499a2.752 2.752 0 0 1-5.504 0V14.75A2.75 2.75 0 0 1 4.752 12m0 1.5c-.692 0-1.252.561-1.252 1.252v4.499a1.252 1.252 0 1 0 2.504 0V14.75c0-.691-.56-1.251-1.252-1.251");
}

</style>
