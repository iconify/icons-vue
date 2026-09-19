<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkus8acxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-laptop-chromebook" /></template>
<style>
.vkus8acxb {
  fill: currentColor;
  d: path("M23 18h-1V5c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v13H1c-.55 0-1 .45-1 1s.45 1 1 1h22c.55 0 1-.45 1-1s-.45-1-1-1m-9.5 0h-3c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h3c.28 0 .5.22.5.5s-.22.5-.5.5m6.5-3H4V6c0-.55.45-1 1-1h14c.55 0 1 .45 1 1z");
}

</style>
