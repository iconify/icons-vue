<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0_tp9tgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-volume-mute" /></template>
<style>
.d0_tp9tgh {
  fill: currentColor;
  d: path("M14 8.83v6.34L11.83 13H9v-2h2.83zM16 4l-5 5H7v6h4l5 5z");
}

</style>
