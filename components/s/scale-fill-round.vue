<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi028cczs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scale-fill-round" /></template>
<style>
.qi028cczs {
  fill: currentColor;
  d: path("M11 3a1 1 0 0 1 2 0v2h5.002c.4.001.76.239.917.606l3 7a1 1 0 0 1 .004.779a4.251 4.251 0 0 1-7.846 0a1 1 0 0 1 .004-.779L16.483 7H13v13h3a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2h3V7H7.517l2.402 5.606a1 1 0 0 1 .004.779a4.25 4.25 0 0 1-7.846 0a1 1 0 0 1 .004-.779l3-7A1 1 0 0 1 6 5h5Z");
}

</style>
