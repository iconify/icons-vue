<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yupshg1vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-camera-roll" /></template>
<style>
.yupshg1vd {
  fill: currentColor;
  d: path("M14 5c0-1.1-.9-2-2-2h-1V2c0-.55-.45-1-1-1H6c-.55 0-1 .45-1 1v1H4c-1.1 0-2 .9-2 2v15c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2h8V5zm6 13h-8v2H4V5h3V3h2v2h3v2h8zM9 15h2v2H9zm0-7h2v2H9zm4 7h2v2h-2zm0-7h2v2h-2zm4 7h2v2h-2zm0-7h2v2h-2z");
}

</style>
