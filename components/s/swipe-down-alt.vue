<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubntvszku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe-down-alt" /></template>
<style>
.ubntvszku {
  fill: currentColor;
  d: path("m12 21l-3.308-3.308l.708-.713l2.1 2.1v-5.102q-1.725-.215-2.863-1.472T7.5 9.5q0-1.864 1.318-3.182T12 5t3.182 1.318T16.5 9.5q0 1.748-1.137 3.005T12.5 13.977v5.102l2.1-2.094l.708.707z");
}

</style>
