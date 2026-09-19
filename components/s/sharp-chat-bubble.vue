<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykjv5hbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-chat-bubble" /></template>
<style>
.ykjv5hbpp {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h16z");
}

</style>
