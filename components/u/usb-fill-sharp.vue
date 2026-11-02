<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fostj_qni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:usb-fill-sharp" /></template>
<style>
.fostj_qni {
  fill: currentColor;
  d: path("m8.293 5.293l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414L13 5.414v8.172l2-2V10a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-.936-.649l-1.889 1.888a3 3 0 1 1-2.35 0l-2.431-2.43a3 3 0 1 1 .573-2.256L11 13.586V5.414L9.707 6.707a.999.999 0 1 1-1.414-1.414");
}

</style>
