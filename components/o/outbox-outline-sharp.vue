<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftb7nsblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:outbox-outline-sharp" /></template>
<style>
.ftb7nsblh {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14v-3h-3q-.75.95-1.787 1.475T12 18t-2.212-.525T8 16H5zm8.725-3.55Q14.5 14.9 14.8 14H19V5H5v9h4.2q.3.9 1.075 1.45T12 16t1.725-.55M5 19h14zm6-5V9.85l-1.6 1.6L8 10l4-4l4 4l-1.4 1.45l-1.6-1.6V14z");
}

</style>
