<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6xg4mbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-portrait-long" /></template>
<style>
.f6xg4mbkj {
  fill: currentColor;
  d: path("M5 9.77V7.845h.923v-2.23q0-.678.457-1.147T7.539 4q.655 0 1.36.347t1.292.603q.467.206 1.006.441q.54.236 1.174.503q.454.218.724.612t.27.873v11.775q0 .856-.703 1.302q-.704.446-1.462.1q-1.12-.458-2.249-.835t-1.855-.577q-.54-.13-.857-.584t-.316-1.02v-1.31H5v-1.922h.923V9.769zM14.385 19V7.379q0-.977-.602-1.628t-1.767-1.074L10.474 4h5.91q.67 0 1.143.472q.472.472.472 1.144v11.769q0 .67-.472 1.143q-.472.472-1.143.472z");
}

</style>
