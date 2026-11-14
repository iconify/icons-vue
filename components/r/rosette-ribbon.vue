<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xasbqkbsi"/><path class="nywe6odcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rosette-ribbon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nywe6odcd {
  d: path("M9.5 8.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-2 4.5L6 21l2.5-1.25l2 1.25l-.5-7.25m6.5-.5L18 21l-2.5-1.25l-2 1.25l.5-7.25");
}

.xasbqkbsi {
  d: path("m12.9 2.925l.828.621a1.5 1.5 0 0 0 .606.271l1.185.237a1.5 1.5 0 0 1 1.177 1.177l.237 1.185a1.5 1.5 0 0 0 .271.606l.621.828a1.5 1.5 0 0 1 0 1.8l-.621.828a1.5 1.5 0 0 0-.271.606l-.237 1.185a1.5 1.5 0 0 1-1.177 1.177l-1.185.237a1.5 1.5 0 0 0-.606.271l-.828.621a1.5 1.5 0 0 1-1.8 0l-.828-.621a1.5 1.5 0 0 0-.606-.271l-1.185-.237a1.5 1.5 0 0 1-1.177-1.177l-.237-1.185a1.5 1.5 0 0 0-.271-.606l-.621-.828a1.5 1.5 0 0 1 0-1.8l.621-.828a1.5 1.5 0 0 0 .271-.606l.237-1.185a1.5 1.5 0 0 1 1.177-1.177l1.185-.237a1.5 1.5 0 0 0 .606-.271l.828-.621a1.5 1.5 0 0 1 1.8 0");
}

</style>
