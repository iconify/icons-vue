<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mokov8tpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-space-dashboard" /></template>
<style>
.mokov8tpu {
  fill: currentColor;
  d: path("M11 21H3V3h8zm2 0h8v-9h-8zm8-11V3h-8v7z");
}

</style>
