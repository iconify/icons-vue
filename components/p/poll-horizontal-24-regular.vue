<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmo67pblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:poll-horizontal-24-regular" /></template>
<style>
.hmo67pblw {
  fill: currentColor;
  d: path("M22 11.752a2.75 2.75 0 0 1-2.751 2.752h-14.5A2.752 2.752 0 1 1 4.75 9h14.5A2.75 2.75 0 0 1 22 11.752m-5 7a2.75 2.75 0 0 1-2.751 2.752h-9.5a2.752 2.752 0 1 1 0-5.504h9.5A2.75 2.75 0 0 1 17 18.752m-5-14a2.75 2.75 0 0 1-2.752 2.752H4.75A2.752 2.752 0 1 1 4.75 2h4.498A2.75 2.75 0 0 1 12 4.752m8.5 7c0-.692-.56-1.252-1.251-1.252h-14.5a1.252 1.252 0 0 0 0 2.504h14.5c.69 0 1.251-.56 1.251-1.252m-5 7c0-.691-.56-1.252-1.251-1.252h-9.5a1.252 1.252 0 0 0 0 2.504h9.5c.69 0 1.251-.56 1.251-1.252m-5-14c0-.692-.56-1.252-1.252-1.252H4.75a1.252 1.252 0 1 0 0 2.504h4.498c.692 0 1.252-.56 1.252-1.252");
}

</style>
