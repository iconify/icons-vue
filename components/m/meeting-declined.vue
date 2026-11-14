<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qegwmxbns"/><path class="hwkzlfygx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meeting-declined" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hwkzlfygx {
  d: path("M7 19.5c0-2.25 1.5-3.5 3.5-3.5s3.5 1.25 3.5 3.5M3 3l18 18");
}

.qegwmxbns {
  d: path("M8.475 4.5h8.65q.107 0 .215.005q.107.006.214.016t.213.026t.212.037t.209.047t.207.057t.204.068t.2.077t.197.087t.191.097q.095.05.187.105q.092.056.182.115q.089.06.175.124t.169.132t.163.14t.156.148t.148.156t.14.163t.132.169t.124.175t.115.182q.055.092.105.187q.051.094.097.191q.046.098.087.197t.077.2t.068.204q.031.103.057.207t.047.209t.037.212t.026.213t.016.214t.005.215v6.25q0 .5-.113.988q-.113.487-.333.937m-5.535 2.45H6.875q-.107 0-.215-.005q-.107-.006-.214-.016t-.213-.026t-.212-.037t-.209-.047q-.104-.026-.207-.057t-.204-.068q-.101-.036-.2-.077t-.197-.087t-.191-.097q-.095-.05-.187-.105q-.092-.056-.182-.115q-.089-.06-.175-.124t-.169-.132t-.163-.14t-.156-.148t-.148-.156t-.14-.163t-.132-.169t-.124-.175q-.059-.09-.115-.182q-.055-.092-.105-.187q-.051-.094-.097-.191q-.046-.098-.087-.197t-.077-.2t-.068-.204t-.057-.207t-.047-.209t-.037-.212t-.026-.213t-.016-.214t-.005-.215v-6.25q0-.502.114-.991q.113-.489.335-.94");
}

</style>
