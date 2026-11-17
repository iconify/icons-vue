<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txo7hqp3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-fill-round" /></template>
<style>
.txo7hqp3b {
  fill: currentColor;
  d: path("M16.275 15.032L8.826 7.584l2.896-3.641A1.697 1.697 0 0 1 14.75 5v3a.997.997 0 0 0 1 1H17a1.966 1.966 0 0 1 1.538 3.188ZM2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414l-4.524-4.524l-1.491 1.874A1.699 1.699 0 0 1 9.25 19v-3a.997.997 0 0 0-1-1H7a1.966 1.966 0 0 1-1.538-3.188l.858-1.078l-5.027-5.027a.999.999 0 1 1 1.414-1.414");
}

</style>
