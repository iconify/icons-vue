<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szsgadypq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:music-video-rounded" /></template>
<style>
.szsgadypq {
  fill: currentColor;
  d: path("M12.294 15.967q.59-.59.59-1.428V9h1.847q.31 0 .54-.22t.229-.55q0-.309-.23-.539t-.54-.23h-1.845q-.31 0-.54.23t-.23.54v4.73q-.248-.205-.565-.323t-.684-.119q-.839 0-1.43.59q-.59.591-.59 1.43t.59 1.428t1.43.59t1.428-.59M4.615 19q-.69 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
