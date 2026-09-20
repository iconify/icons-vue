<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lq-0nct7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-arrow-left-20-filled" /></template>
<style>
.lq-0nct7d {
  fill: currentColor;
  d: path("M5.496 3a2.5 2.5 0 0 0-2.5 2.5v4.102A5.5 5.5 0 0 1 10.4 17h4.096a2.5 2.5 0 0 0 2.5-2.5V7h-7.5a1.5 1.5 0 0 1-1.5-1.5V3zm3.5 0v2.5a.5.5 0 0 0 .5.5h7.5v-.5a2.5 2.5 0 0 0-2.5-2.5zM10 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-6.853-.354l-.003.003a.5.5 0 0 0-.144.348v.006a.5.5 0 0 0 .146.35l2 2a.5.5 0 0 0 .708-.707L4.707 15H7.5a.5.5 0 0 0 0-1H4.707l1.147-1.146a.5.5 0 0 0-.708-.708z");
}

</style>
