<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ims9g68sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:medal-16-regular" /></template>
<style>
.ims9g68sk {
  fill: currentColor;
  d: path("M10.867 1a2.5 2.5 0 0 1 2.145 1.214l.632 1.054c.233.388.356.833.356 1.286v.09a2.5 2.5 0 0 1-.42 1.387l-2.518 3.775a3.5 3.5 0 1 1-6.125.001L2.42 6.03A2.5 2.5 0 0 1 2 4.645v-.091a2.5 2.5 0 0 1 .356-1.286l.632-1.054A2.5 2.5 0 0 1 5.133 1zM8 9a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5M4.035 2.48q-.106.112-.19.249l-.631 1.053A1.5 1.5 0 0 0 3 4.554v.09c0 .297.088.586.252.833l2.33 3.494c.428-.41.961-.713 1.555-.864L4.31 3.867a1.85 1.85 0 0 1-.275-1.388m7.929 0a1.85 1.85 0 0 1-.274 1.386l-2.829 4.24c.595.15 1.128.454 1.557.865l2.33-3.494A1.5 1.5 0 0 0 13 4.645v-.091a1.5 1.5 0 0 0-.214-.772l-.632-1.053a1.5 1.5 0 0 0-.19-.25M8 7.598L9.732 5H6.268zM5.844 2a.844.844 0 0 0-.702 1.312L5.6 4h4.798l.46-.688A.845.845 0 0 0 10.155 2z");
}

</style>
