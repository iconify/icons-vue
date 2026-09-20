<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_znzubpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:voice-chat-outline-sharp" /></template>
<style>
.i_znzubpf {
  fill: currentColor;
  d: path("M6.308 10.5h.884v-1h-.884zm2.5 2h.884v-5h-.884zm2.75 2h.884v-9h-.884zm2.75-2h.884v-5h-.884zm2.5-2h.884v-1h-.884zM3 20.077V3h18v14H6.077zM5.65 16H20V4H4v13.644zM4 16V4z");
}

</style>
