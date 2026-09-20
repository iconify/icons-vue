<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un0mt6dmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:science-off" /></template>
<style>
.un0mt6dmh {
  fill: currentColor;
  d: path("m14 11.31l-4-4V5H8.616q-.213 0-.357-.144t-.143-.357t.143-.356T8.616 4h6.769q.212 0 .356.144t.144.357t-.144.356t-.356.143H14zm5.223 9.482L18.431 20H5q-.639 0-.908-.57t.127-1.065L9.9 11.47L3.17 4.74l.707-.708l16.054 16.054z");
}

</style>
