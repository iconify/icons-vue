<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcx0myb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videocam-outline-sharp" /></template>
<style>
.zcx0myb8t {
  fill: currentColor;
  d: path("M3.48 19V5h14v6.27l3.04-3.04v7.54l-3.04-3.04V19zm1-1h12V6h-12zm0 0V6z");
}

</style>
