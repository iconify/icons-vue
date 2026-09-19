<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjfqxnb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-area-chart" /></template>
<style>
.yjfqxnb-m {
  fill: currentColor;
  d: path("M3 13v7h18v-1.5l-9-7L8 17zm0-6l4 3l5-7l5 4h4v8.97l-9.4-7.31l-3.98 5.48L3 10.44z");
}

</style>
