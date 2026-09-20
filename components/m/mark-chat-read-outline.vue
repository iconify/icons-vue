<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuwhwgb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-chat-read-outline" /></template>
<style>
.wuwhwgb-w {
  fill: currentColor;
  d: path("m17.35 19.289l-2.813-2.839l.688-.688l2.125 2.125l4.25-4.25l.688.713zM3 20.077V4.616q0-.691.463-1.153T4.615 3h14.77q.69 0 1.152.463T21 4.616V11.5h-1V4.616q0-.231-.192-.424T19.385 4H4.615q-.23 0-.423.192T4 4.615v13.03L5.65 16h6.85v1H6.077zM4 16v1.385V4z");
}

</style>
