<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqr9u7bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-camera-indoor" /></template>
<style>
.xqr9u7bwd {
  fill: currentColor;
  d: path("M12 3L4 9v12h16V9zm4 13.06L14 15v2H8v-6h6v2l2-1.06z");
}

</style>
