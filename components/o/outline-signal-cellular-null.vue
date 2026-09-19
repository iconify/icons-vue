<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-nf5tb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-signal-cellular-null" /></template>
<style>
.g-nf5tb5r {
  fill: currentColor;
  d: path("M20 6.83V20H6.83zM22 2L2 22h20z");
}

</style>
