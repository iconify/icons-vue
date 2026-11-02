<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsgzgrb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-outgoing-fill-sharp" /></template>
<style>
.qsgzgrb1o {
  fill: currentColor;
  d: path("M2 5V3a1 1 0 0 1 1-1h6c.409 0 .777.249.928.629l2 5a1 1 0 0 1-.221 1.078L9.414 11L13 14.586l2.293-2.293a1 1 0 0 1 1.078-.221l5 2c.38.151.629.519.629.928v6a1 1 0 0 1-1 1h-2C9.611 22 2 14.389 2 5m18 2V5.414l-4.293 4.293a.999.999 0 1 1-1.414-1.414L18.586 4H17a1 1 0 0 1 0-2h4a.997.997 0 0 1 1 1v4a1 1 0 0 1-2 0");
}

</style>
