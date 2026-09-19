<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no0tjj59n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-cleaning-services" /></template>
<style>
.no0tjj59n {
  fill: currentColor;
  d: path("M15 11V1H9v10H3v12h18V11zm4 10h-2v-4h-2v4h-2v-4h-2v4H9v-4H7v4H5v-8h14z");
}

</style>
