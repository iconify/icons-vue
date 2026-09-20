<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygtssqlkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-chat-read" /></template>
<style>
.ygtssqlkg {
  fill: currentColor;
  d: path("m17.35 19.289l-2.813-2.839l.688-.688l2.125 2.125l4.25-4.25l.688.713zM3 20.077V4.616q0-.691.463-1.153T4.615 3h14.77q.69 0 1.152.463T21 4.616V11.5h-8.5V17H6.077z");
}

</style>
