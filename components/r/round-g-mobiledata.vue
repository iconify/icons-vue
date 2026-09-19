<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztg5ofbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-g-mobiledata" /></template>
<style>
.ztg5ofbmm {
  fill: currentColor;
  d: path("M12 12c0 .55.45 1 1 1h1v2H9V9h6c.55 0 1-.45 1-1s-.45-1-1-1H9c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h5c1.1 0 2-.9 2-2v-3c0-.55-.45-1-1-1h-2c-.55 0-1 .45-1 1");
}

</style>
