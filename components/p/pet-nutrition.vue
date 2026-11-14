<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwrfmw15y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-nutrition" /></template>
<style>
.wwrfmw15y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.578 14.992q-.084.008-.169.008H5.591q-.143 0-.285-.023q-.141-.024-.277-.07t-.262-.113q-.127-.068-.241-.155t-.211-.192q-.099-.104-.178-.223q-.08-.12-.139-.25q-.06-.131-.097-.269l-.807-3q-.026-.097-.041-.196t-.018-.2q-.004-.1.005-.2q.008-.1.027-.199q.02-.098.05-.194q.031-.095.072-.187q.041-.091.093-.177t.113-.166t.13-.152t.148-.136q.077-.064.161-.118q.085-.055.175-.099t.184-.078t.192-.057t.198-.034t.2-.012h10.434q.1 0 .2.012q.1.011.198.034q.097.023.192.057q.094.034.184.078t.175.099q.084.054.161.118q.078.064.148.136t.13.152q.061.08.113.166t.093.177q.041.092.072.187q.03.096.05.194q.019.099.027.199t.005.2q-.003.101-.018.2t-.041.196l-.719 2.674M4 8.5a2.5 2.5 0 0 1 4.5-2a3 3 0 0 1 5-.5A2.75 2.75 0 0 1 16 8.5m.25 11.75C15.75 16.5 18 14.5 22 14.5c0 4-2 6.25-5.75 5.75M15 21.75l4-4");
}

</style>
