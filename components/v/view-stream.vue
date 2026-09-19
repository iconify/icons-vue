<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5vn_u__e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:view-stream" /></template>
<style>
.t5vn_u__e {
  fill: currentColor;
  d: path("M3 17v-2c0-1.1.9-2 2-2h14c1.1 0 2 .9 2 2v2c0 1.1-.9 2-2 2H5c-1.1 0-2-.9-2-2M3 7v2c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2H5c-1.1 0-2 .9-2 2");
}

</style>
