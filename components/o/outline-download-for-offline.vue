<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7txafbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-download-for-offline" /></template>
<style>
.o7txafbns {
  fill: currentColor;
  d: path("M12 2C6.49 2 2 6.49 2 12s4.49 10 10 10s10-4.49 10-10S17.51 2 12 2m0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8s8 3.59 8 8s-3.59 8-8 8m2.59-11.41L16 10l-4 4l-4-4l1.41-1.41L11 10.17V6h2v4.17zM17 17H7v-2h10z");
}

</style>
