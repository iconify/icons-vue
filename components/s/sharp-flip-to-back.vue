<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdklxv_jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-flip-to-back" /></template>
<style>
.sdklxv_jt {
  fill: currentColor;
  d: path("M9 7H7v2h2zm0 4H7v2h2zm4 4h-2v2h2zm0-12h-2v2h2zM9 3H7v2h2zm12 0h-2v2h2zm0 12h-2v2h2zM9 15H7v2h2zm10-2h2v-2h-2zm0-4h2V7h-2zM5 7H3v14h14v-2H5zm10-2h2V3h-2zm0 12h2v-2h-2z");
}

</style>
