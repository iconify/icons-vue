<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lrqx-kbjc"/><path class="cwempnb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patent-gear" /></template>
<style>
.cwempnb0o {
  d: path("m11.5 6.358l.007-.112A.494.494 0 0 1 12 5.781a.494.494 0 0 1 .493.465l.007.112a.72.72 0 0 0 .441.62a.72.72 0 0 0 .751-.127l.083-.074a.494.494 0 0 1 .678.02a.494.494 0 0 1 .02.678l-.074.083a.72.72 0 0 0-.127.751a.72.72 0 0 0 .62.441l.112.007a.494.494 0 0 1 .465.493a.494.494 0 0 1-.465.493l-.112.007a.72.72 0 0 0-.62.441a.72.72 0 0 0 .127.751l.074.083a.494.494 0 0 1-.02.678a.494.494 0 0 1-.678.02l-.083-.074a.72.72 0 0 0-.751-.127a.72.72 0 0 0-.441.62l-.007.112a.494.494 0 0 1-.493.465a.494.494 0 0 1-.493-.465l-.007-.112a.72.72 0 0 0-.441-.62a.72.72 0 0 0-.751.127l-.083.074a.494.494 0 0 1-.678-.02a.494.494 0 0 1-.02-.678l.074-.083a.72.72 0 0 0 .127-.751a.72.72 0 0 0-.62-.441l-.112-.007a.494.494 0 0 1-.465-.493a.494.494 0 0 1 .465-.493l.112-.007a.72.72 0 0 0 .62-.441a.72.72 0 0 0-.127-.751l-.074-.083a.494.494 0 0 1 .02-.678a.494.494 0 0 1 .678-.02l.083.074a.72.72 0 0 0 .751.127a.72.72 0 0 0 .441-.62");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrqx-kbjc {
  d: path("M9 18v-2.5C6.75 14 5.25 11.75 5.25 9.25a6.75 6.75 0 0 1 13.5 0c0 2.5-1.5 4.75-3.75 6.25V18Zm1.25 3h3.5");
}

</style>
