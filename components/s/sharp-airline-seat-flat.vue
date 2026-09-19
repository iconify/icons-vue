<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9g9lgw2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-airline-seat-flat" /></template>
<style>
.x9g9lgw2t {
  fill: currentColor;
  d: path("M22 7v6H9V7zM2 14v2h6v2h8v-2h6v-2zm5.14-1.9a3 3 0 0 0-.04-4.24a3 3 0 0 0-4.24.04a3 3 0 0 0 .04 4.24a3 3 0 0 0 4.24-.04");
}

</style>
