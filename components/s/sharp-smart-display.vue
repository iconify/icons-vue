<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkerpptjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-smart-display" /></template>
<style>
.wkerpptjt {
  fill: currentColor;
  d: path("M22 4H2v16h20zM9.5 16.5v-9l7 4.5z");
}

</style>
