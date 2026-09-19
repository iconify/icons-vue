<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr0lnn_id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-queue-music" /></template>
<style>
.tr0lnn_id {
  fill: currentColor;
  d: path("M15 6H3v2h12zm0 4H3v2h12zM3 16h8v-2H3zM17 6v8.18c-.31-.11-.65-.18-1-.18c-1.66 0-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3V8h3V6z");
}

</style>
