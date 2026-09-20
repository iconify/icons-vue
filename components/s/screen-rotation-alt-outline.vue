<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz424mbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screen-rotation-alt-outline" /></template>
<style>
.yz424mbfo {
  fill: currentColor;
  d: path("M12.175 21.4L3.75 13H6.6l7 7l5-5H16v-2h6v6h-2v-2.6l-5 5q-.575.575-1.412.575t-1.413-.575M2 11V5h2v2.6l5-5q.575-.575 1.413-.575t1.412.575L20.25 11H17.4l-7-7l-5 5H8v2z");
}

</style>
