<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5bd6u2jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-voice-chat" /></template>
<style>
.n5bd6u2jk {
  fill: currentColor;
  d: path("M22 2H2.01L2 22l4-4h16zm-4 12l-4-3.2V14H6V6h8v3.2L18 6z");
}

</style>
