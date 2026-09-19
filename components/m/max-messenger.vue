<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n5ql-q7kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:max-messenger" /></template>
<style>
.n5ql-q7kv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.63 40.465c8.083 7.193 27.86-1.166 27.783-15.85C43.36 14.546 35.107 4.59 24.873 4.5c-9.538-.083-19.648 5.962-20.23 17.767c-.172 3.515 0 8.859 1.231 11.73c2.335 6.7.113 8.477 2.804 9.328q3.617.9 6.953-2.861");
}

</style>
