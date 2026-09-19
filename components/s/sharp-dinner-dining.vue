<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhh02en6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-dinner-dining" /></template>
<style>
.xhh02en6j {
  fill: currentColor;
  d: path("m2 19l2 2h16l2-2zm1-1h16.97c.29-3.26-2.28-6-5.48-6c-2.35 0-4.35 1.48-5.14 3.55c-.41-.23-.87-.38-1.35-.47V9h4V6.75h9v-1.5h-9V3H3v1.5h1v.75H3v1.5h1v.75H3V9h1v7.39c-.44.46-.78 1-1 1.61M8 7.5v-.75h2v.75zm2-2.25H8V4.5h2zM5.5 4.5h1v.75h-1zm0 2.25h1v.75h-1zM6.5 9v6.06c-.35.06-.68.17-1 .3V9z");
}

</style>
