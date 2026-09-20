<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t9ab91p5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:view-desktop-20-filled" /></template>
<style>
.t9ab91p5q {
  fill: currentColor;
  d: path("M1.962 4.5a1.5 1.5 0 0 1 1.5-1.5h12.94a1.5 1.5 0 0 1 1.5 1.5v8a1.5 1.5 0 0 1-1.5 1.5H12v2.015h1.499a.5.5 0 0 1 0 1h-7a.5.5 0 1 1 0-1h1.5V14H3.463a1.5 1.5 0 0 1-1.5-1.5zM9 14v2.015h2V14zM4 5.5v6a.5.5 0 0 0 .5.5h.998a.5.5 0 0 0 .5-.5v-6a.5.5 0 0 0-.5-.5H4.5a.5.5 0 0 0-.5.5m3 0v6a.5.5 0 0 0 .5.5h8a.5.5 0 0 0 .5-.5v-6a.5.5 0 0 0-.5-.5h-8a.5.5 0 0 0-.5.5");
}

</style>
