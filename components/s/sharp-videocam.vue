<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efk3_mi9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-videocam" /></template>
<style>
.efk3_mi9r {
  fill: currentColor;
  d: path("M17 10.5V6H3v12h14v-4.5l4 4v-11z");
}

</style>
