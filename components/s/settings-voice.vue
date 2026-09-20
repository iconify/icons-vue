<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3eapcxiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-voice" /></template>
<style>
.f3eapcxiu {
  fill: currentColor;
  d: path("M7.46 23.54q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m4.54.23q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m3.46-.23q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m-4.883-11.117Q10 11.846 10 11V5q0-.846.577-1.423T12 3t1.423.577T14 5v6q0 .846-.577 1.423T12 13t-1.423-.577M11.5 20.5v-3.485q-2.35-.234-3.925-1.947T6 11h1q0 2.075 1.463 3.538T12 16t3.538-1.463T17 11h1q0 2.356-1.575 4.068T12.5 17.015V20.5z");
}

</style>
