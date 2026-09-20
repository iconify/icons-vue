<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="tv6tk0ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rhombus-28-filled" /></template>
<style>
.tv6tk0ben {
  fill: currentColor;
  d: path("M6.555 5.928A3 3 0 0 1 9.357 4h14.638c2.103 0 3.553 2.107 2.802 4.072l-5.354 14A3 3 0 0 1 18.641 24H4.003C1.9 24 .45 21.893 1.2 19.928z");
}

</style>
