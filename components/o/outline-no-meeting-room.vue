<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahu_lhsun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-no-meeting-room" /></template>
<style>
.ahu_lhsun {
  fill: currentColor;
  d: path("M12 5v3.88l2 2V6h3v7.88l2 2V4h-5V3H6.12l2 2zM2.41 2.13L1 3.54l4 4V19H3v2h11v-4.46L20.46 23l1.41-1.41zM12 19H7V9.54l5 5z");
}

</style>
