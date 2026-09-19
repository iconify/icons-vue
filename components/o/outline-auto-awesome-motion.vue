<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo7acll6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-auto-awesome-motion" /></template>
<style>
.bo7acll6w {
  fill: currentColor;
  d: path("M14 2H4c-1.1 0-2 .9-2 2v10h2V4h10zm4 4H8c-1.1 0-2 .9-2 2v10h2V8h10zm2 4h-8c-1.1 0-2 .9-2 2v8c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2v-8c0-1.1-.9-2-2-2m0 10h-8v-8h8z");
}

</style>
