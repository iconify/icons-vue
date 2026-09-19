<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3ga_jbqh"/><circle class="k79q3xboj"/><path class="slc7el2vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-loyalty" /></template>
<style>
.i3ga_jbqh {
  fill: currentColor;
  d: path("m21.41 11.58l-9-9C12.05 2.22 11.55 2 11 2H4c-1.1 0-2 .9-2 2v7c0 .55.22 1.05.59 1.42l9 9c.36.36.86.58 1.41.58s1.05-.22 1.41-.59l7-7c.37-.36.59-.86.59-1.41s-.23-1.06-.59-1.42M13 20.01L4 11V4h7v-.01l9 9z");
}

.k79q3xboj {
  cx: 6.5px;
  cy: 6.5px;
  r: 1.5px;
  fill: currentColor;
}

.slc7el2vp {
  fill: currentColor;
  d: path("M8.9 12.55c0 .57.23 1.07.6 1.45l3.5 3.5l3.5-3.5a2.053 2.053 0 0 0-2.9-2.9l-.6.6l-.6-.59c-.37-.38-.89-.61-1.45-.61c-1.13 0-2.05.92-2.05 2.05");
}

</style>
