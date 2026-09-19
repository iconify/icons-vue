<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvc0pi9ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-flip" /></template>
<style>
.mvc0pi9ca {
  fill: currentColor;
  d: path("M15 21h2v-2h-2zm4-12h2V7h-2zM3 3v18h6v-2H5V5h4V3zm16 0v2h2V3zm-8 20h2V1h-2zm8-6h2v-2h-2zM15 5h2V3h-2zm4 8h2v-2h-2zm0 8h2v-2h-2z");
}

</style>
