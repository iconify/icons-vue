<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yfhyt6bqf"/><path class="yol9b_wkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patent-certificate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yfhyt6bqf {
  d: path("M6.382 17.104q-.211-.111-.406-.249t-.369-.301t-.325-.349t-.275-.39q-.123-.204-.218-.423q-.095-.22-.16-.45q-.064-.23-.097-.466Q4.5 14.239 4.5 14V6q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323t.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T8 2.5h8q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T19.5 6v8q0 .244-.034.485q-.033.241-.1.475t-.166.457q-.098.223-.227.429q-.128.207-.284.394t-.336.351t-.382.301q-.201.137-.419.245M8.5 6h7m-7 3.5H13");
}

.yol9b_wkz {
  d: path("M10.25 18a3 3 0 1 1 3.5 0l1 3.5L12 20.25L9.25 21.5Z");
}

</style>
