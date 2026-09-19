<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltdk4zbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-signal-cellular-off" /></template>
<style>
.ltdk4zbph {
  fill: currentColor;
  d: path("m21 1l-8.31 8.31l8.31 8.3zM4.91 4.36L3.5 5.77l6.36 6.37L1 21h17.73l2 2l1.41-1.41z");
}

</style>
