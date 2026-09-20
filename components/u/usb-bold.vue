<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fc4v5mblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:usb-bold" /></template>
<style>
.fc4v5mblr {
  fill: currentColor;
  d: path("m251.2 118.4l-48-36A12 12 0 0 0 184 92v24H76V76h22.06a36 36 0 1 0 0-24H72a20 20 0 0 0-20 20v44H12a12 12 0 0 0 0 24h40v44a20 20 0 0 0 20 20h24v4a20 20 0 0 0 20 20h32a20 20 0 0 0 20-20v-32a20 20 0 0 0-20-20h-32a20 20 0 0 0-20 20v4H76v-40h108v24a12 12 0 0 0 19.2 9.6l48-36a12 12 0 0 0 0-19.2M132 52a12 12 0 1 1-12 12a12 12 0 0 1 12-12m-12 128h24v24h-24Zm88-40v-24l16 12Z");
}

</style>
