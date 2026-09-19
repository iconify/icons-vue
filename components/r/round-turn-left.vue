<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6hjs0rqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-turn-left" /></template>
<style>
.b6hjs0rqq {
  fill: currentColor;
  d: path("M7.71 13.29a.996.996 0 0 1-1.41 0L3.71 10.7a.996.996 0 0 1 0-1.41L6.3 6.7a.996.996 0 1 1 1.41 1.41L6.83 9H15c1.1 0 2 .9 2 2v8c0 .55-.45 1-1 1s-1-.45-1-1v-8H6.83l.88.88c.39.39.39 1.02 0 1.41");
}

</style>
