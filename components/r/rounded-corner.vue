<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw5lloppe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:rounded-corner" /></template>
<style>
.zw5lloppe {
  fill: currentColor;
  d: path("M19 19h2v2h-2zm0-2h2v-2h-2zM3 13h2v-2H3zm0 4h2v-2H3zm0-8h2V7H3zm0-4h2V3H3zm4 0h2V3H7zm8 16h2v-2h-2zm-4 0h2v-2h-2zm4 0h2v-2h-2zm-8 0h2v-2H7zm-4 0h2v-2H3zM21 8c0-2.76-2.24-5-5-5h-5v2h5c1.65 0 3 1.35 3 3v5h2z");
}

</style>
