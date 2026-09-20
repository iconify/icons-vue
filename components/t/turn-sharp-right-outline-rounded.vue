<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbhg5-b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-sharp-right-outline-rounded" /></template>
<style>
.wbhg5-b0e {
  fill: currentColor;
  d: path("M6.509 19.857q-.143-.143-.143-.357v-4.77q0-.67.472-1.142t1.143-.472h7.769q.27 0 .442-.174q.174-.173.174-.442V5.916l-1.747 1.746q-.16.16-.353.16q-.195 0-.354-.16q-.16-.16-.15-.364t.15-.344L16.3 4.566q.242-.243.566-.243t.565.243l2.388 2.388q.16.16.16.354t-.16.354t-.363.15t-.344-.15l-1.746-1.746V12.5q0 .671-.473 1.143q-.472.472-1.143.472H7.98q-.268 0-.441.174t-.173.442V19.5q0 .214-.144.357q-.143.143-.357.143q-.213 0-.356-.143");
}

</style>
