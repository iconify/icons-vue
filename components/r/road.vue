<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx09o2p9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:road" /></template>
<style>
.qx09o2p9m {
  fill: currentColor;
  d: path("M4 20V4h2v16zm7 0v-4h2v4zm7 0V4h2v16zm-7-6v-4h2v4zm0-6V4h2v4z");
}

</style>
