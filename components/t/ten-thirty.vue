<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="n99huxb6x"/><path class="x052y76kt"/><path class="kkxkj4b-q"/><path class="kmn__ju0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:ten-thirty" /></template>
<style>
.kkxkj4b-q {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M29.899 52.57c0 1.429.844 2.587 1.877 2.587c1.037 0 1.876-1.158 1.876-2.587V31.643c0-1.429-.84-2.584-1.876-2.584c-1.033 0-1.877 1.156-1.877 2.584z");
}

.kmn__ju0l {
  fill: var(--svg-color--788288, #788288);
  d: path("M20.446 19.907c-1.131-.87-2.562-.909-3.195-.088c-.628.821-.224 2.193.908 3.065l12 9.235c1.129.87 2.562.906 3.19.086c.631-.821.229-2.193-.903-3.062z");
}

.n99huxb6x {
  cx: 31.761px;
  cy: 31.765px;
  r: 29.425px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

.x052y76kt {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M0 31.765C0 49.28 14.249 63.53 31.763 63.53s31.764-14.25 31.764-31.765S49.277 0 31.763 0S0 14.25 0 31.765m6.184 0c0-14.1 11.476-25.579 25.579-25.579c14.1 0 25.583 11.476 25.583 25.579c0 14.11-11.479 25.583-25.583 25.583c-14.1 0-25.579-11.477-25.579-25.583");
}

</style>
