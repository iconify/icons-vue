<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsmckdbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-arrow-right" /></template>
<style>
.dsmckdbwm {
  fill: currentColor;
  d: path("m10 17l5-5l-5-5z");
}

</style>
