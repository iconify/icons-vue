<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jysqg7bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-analytics" /></template>
<style>
.jysqg7bny {
  fill: currentColor;
  d: path("M3 3v18h18V3zm6 14H7v-5h2zm4 0h-2v-3h2zm0-5h-2v-2h2zm4 5h-2V7h2z");
}

</style>
