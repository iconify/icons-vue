<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgec19b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:quiz-new-24-regular" /></template>
<style>
.tgec19b3a {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m0 1.999a.5.5 0 0 0-.5.5V17h-2.505a.5.5 0 0 0 0 1h2.506v2.504a.5.5 0 0 0 1 0V18h2.496a.5.5 0 0 0 0-1H18v-2.501a.5.5 0 0 0-.5-.5M17.75 3A3.25 3.25 0 0 1 21 6.25v5.774a6.5 6.5 0 0 0-1.5-.71V6.25a1.75 1.75 0 0 0-1.75-1.75H6.25A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75h5.065a6.4 6.4 0 0 0 .71 1.5H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zm-6.673 13.5q-.076.49-.077 1q.002.252.021.5H6.75a.75.75 0 0 1 0-1.5zm1.302-3.001a6.5 6.5 0 0 0-.88 1.5H6.75a.75.75 0 0 1 0-1.5zM10 4.996a.75.75 0 0 1 .694.467l2.247 5.503a.75.75 0 1 1-1.388.566l-.423-1.035H8.868l-.424 1.036a.75.75 0 0 1-1.388-.568l2.25-5.502A.75.75 0 0 1 10 4.996m5.75 0a.75.75 0 0 1 .75.75v1.25h1.25a.75.75 0 0 1 0 1.5H16.5v1.25a.75.75 0 0 1-1.5 0v-1.25h-1.25a.75.75 0 0 1 0-1.5H15v-1.25a.75.75 0 0 1 .75-.75M9.481 8.997h1.037L10 7.73z");
}

</style>
