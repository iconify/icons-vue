<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp_bbubdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe-down-alt-outline" /></template>
<style>
.vp_bbubdp {
  fill: currentColor;
  d: path("m12 21l-3.308-3.308l.708-.713l2.1 2.1v-5.102q-1.725-.215-2.863-1.472T7.5 9.5q0-1.864 1.318-3.182T12 5t3.182 1.318T16.5 9.5q0 1.748-1.137 3.005T12.5 13.977v5.102l2.1-2.094l.708.707zm2.48-9.02q1.02-1.018 1.02-2.48t-1.02-2.48T12 6T9.52 7.02T8.5 9.5t1.02 2.48T12 13t2.48-1.02M12 9.5");
}

</style>
