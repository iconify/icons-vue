<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trkdu47da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-multi-room-outline" /></template>
<style>
.trkdu47da {
  fill: currentColor;
  d: path("M4 21V9l8-6l8 6v12zm2-2h7v-3H6zm9 0h3v-3h-3zm-9-5h3v-2.975H6zm5 0h7v-2.975h-7zM7.3 9.025h9.4L12 5.5z");
}

</style>
