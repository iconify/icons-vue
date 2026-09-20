<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl-uws_fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:quickreply-outline" /></template>
<style>
.yl-uws_fl {
  fill: currentColor;
  d: path("M2 22V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v6h-2V4H4v13.125L5.15 16H15v2H6zm2-6V4zm15 7v-5h-2v-6h5l-1.7 4h2.2z");
}

</style>
