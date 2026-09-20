<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbqf99byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reopen-window-rounded" /></template>
<style>
.xbqf99byd {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v4.5q0 .213-.143.356q-.144.144-.357.144t-.357-.144t-.143-.356V8H4v9.385q0 .23.192.423t.423.192h6.039q.213 0 .357.143t.143.357t-.143.357t-.357.143zm13.615 3.385q-1.348 0-2.466-.694q-1.117-.693-1.71-1.854q-.097-.185-.033-.378q.065-.193.236-.28q.16-.067.329.01t.261.236q.488.94 1.39 1.508t1.993.567q1.584 0 2.696-1.112t1.112-2.696t-1.112-2.696t-2.696-1.111q-.95 0-1.768.442T15.032 15.5h1.45q.19 0 .316.126t.126.316t-.126.317t-.316.126h-2.135q-.348 0-.578-.23t-.23-.578v-2.135q0-.19.127-.316T13.98 13t.316.126t.126.316v1.406q.725-.829 1.712-1.339Q17.12 13 18.23 13q1.96 0 3.326 1.366t1.366 3.326t-1.366 3.326t-3.326 1.367");
}

</style>
