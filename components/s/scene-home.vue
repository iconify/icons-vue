<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-9orccbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:scene-home" /></template>
<style>
.e-9orccbv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.513 3.288l4.5-1.5q.115-.038.237-.038h9q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141T18 2.5v14.718l3.314 3.788q.09.103.138.23q.048.128.048.264q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-10q-.095 0-.188-.024q-.092-.024-.176-.07t-.152-.112q-.069-.066-.12-.147l-2.187-3.499l-3.94 1.314q-.07.023-.143.032t-.147.004t-.145-.025q-.071-.019-.137-.052t-.125-.079q-.058-.045-.107-.101q-.048-.055-.085-.12q-.036-.064-.06-.134Q3 19.122 3 19V4q0-.059.009-.117t.027-.113t.045-.109q.026-.052.061-.1q.034-.047.075-.089t.089-.076t.099-.062t.108-.046M9 16.75h7.5V3.25H9zm-1.5.209V3.541l-3 1v13.418zm2.103 1.291l1.563 2.5h7.931l-2.187-2.5z");
}

</style>
