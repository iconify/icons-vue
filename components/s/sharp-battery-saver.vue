<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiokrfqwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-battery-saver" /></template>
<style>
.xiokrfqwu {
  fill: currentColor;
  d: path("M17 4h-3V2h-4v2H7v18h10zm-2 10h-2v2h-2v-2H9v-2h2v-2h2v2h2z");
}

</style>
