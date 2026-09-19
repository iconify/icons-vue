<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4yqv1blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-margin" /></template>
<style>
.b4yqv1blq {
  fill: currentColor;
  d: path("M3 3v18h18V3zm6 10H7v-2h2zm0-4H7V7h2zm4 4h-2v-2h2zm0-4h-2V7h2zm4 4h-2v-2h2zm0-4h-2V7h2z");
}

</style>
