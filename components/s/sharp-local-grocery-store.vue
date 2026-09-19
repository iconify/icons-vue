<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acu273yni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-local-grocery-store" /></template>
<style>
.acu273yni {
  fill: currentColor;
  d: path("M7 18c-1.1 0-1.99.9-1.99 2S5.9 22 7 22s2-.9 2-2s-.9-2-2-2M1 4h2l3.6 7.59L3.62 17H19v-2H7l1.1-2h8.64l4.97-9H5.21l-.94-2H1zm16 14c-1.1 0-1.99.9-1.99 2s.89 2 1.99 2s2-.9 2-2s-.9-2-2-2");
}

</style>
