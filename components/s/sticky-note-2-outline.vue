<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl1fgib1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticky-note-2-outline" /></template>
<style>
.tl1fgib1m {
  fill: currentColor;
  d: path("M5.616 19H14v-5h5V5.616q0-.27-.173-.443T18.385 5H5.615q-.269 0-.442.173T5 5.616v12.769q0 .269.173.442t.443.173m0 1q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h12.769q.67 0 1.143.472q.472.472.472 1.144v8.673L14.288 20zm2.269-6.539v-1H12v1zm0-3.961v-1h8.23v1zM5 19V5z");
}

</style>
