<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4-lehbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-hls" /></template>
<style>
.y4-lehbci {
  fill: currentColor;
  d: path("M6.5 9H8v6H6.5v-2.5h-2V15H3V9h1.5v2h2zm9 6h5v-3.5H17v-1h2v.5h1.5V9h-5v3.5H19v1h-2V13h-1.5zM14 15v-1.5h-2.5V9H10v6z");
}

</style>
