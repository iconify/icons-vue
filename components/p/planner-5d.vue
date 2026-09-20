<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b-1nnac6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:planner-5d" /></template>
<style>
.b-1nnac6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.054 13.069v-3.52m-.241 23.594c0-3.03-2.554-5.486-5.704-5.486s-5.704 2.456-5.704 5.486v3.566c0 3.03 2.554 5.486 5.704 5.486s5.704-2.456 5.704-5.486m0 5.486V20.25M9.187 40.344c1.575 1.27 3.103 1.85 6.922 1.85h.656c3.533 0 6.396-2.753 6.396-6.151s-2.863-6.152-6.396-6.152H9.187v-9.64H23.16M4.268 15.503L24 5.805l19.732 9.698");
}

</style>
