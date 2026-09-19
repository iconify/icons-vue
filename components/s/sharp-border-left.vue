<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu_l_8_8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-border-left" /></template>
<style>
.cu_l_8_8e {
  fill: currentColor;
  d: path("M11 21h2v-2h-2zm0-4h2v-2h-2zm0-12h2V3h-2zm0 4h2V7h-2zm0 4h2v-2h-2zm-4 8h2v-2H7zM7 5h2V3H7zm0 8h2v-2H7zm-4 8h2V3H3zM19 9h2V7h-2zm-4 12h2v-2h-2zm4-4h2v-2h-2zm0-14v2h2V3zm0 10h2v-2h-2zm0 8h2v-2h-2zm-4-8h2v-2h-2zm0-8h2V3h-2z");
}

</style>
