<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz5u8hbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-sell" /></template>
<style>
.rz5u8hbns {
  fill: currentColor;
  d: path("M22.83 12.83L12 2H2v10l10.83 10.83zM6.5 8C5.67 8 5 7.33 5 6.5S5.67 5 6.5 5S8 5.67 8 6.5S7.33 8 6.5 8");
}

</style>
