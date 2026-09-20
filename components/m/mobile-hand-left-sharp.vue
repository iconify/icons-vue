<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_zlvp19k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-hand-left-sharp" /></template>
<style>
.w_zlvp19k {
  fill: currentColor;
  d: path("m12.216 21l5.119-6.471l-3.358-3.493l-3.439 1.7V5.134H7.923V3H19v18zM7.23 21q-1.25 0-2.125-.875T4.23 18v-7.48l3-3h.923v9.038l5.308-2.616l.711.75l-4.477 5.64q-.275.35-.658.51q-.384.158-.815.158zM14 7.078q.23-.23.23-.54T14 6t-.54-.23q-.309 0-.539.23t-.23.54t.23.539q.23.23.54.23t.539-.23");
}

</style>
