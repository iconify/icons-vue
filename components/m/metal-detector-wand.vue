<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1bq55cyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:metal-detector-wand" /></template>
<style>
.y1bq55cyd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.888 14.76L4.606 2.057q-.088-.12-.216-.198q-.127-.077-.275-.1q-.147-.023-.292.012t-.266.123q-.059.044-.109.098t-.089.118q-.038.063-.063.132q-.026.07-.037.143t-.008.147t.02.145t.049.139t.074.127L6.02 6.535L3.809 8.143q-.06.044-.11.098t-.089.117t-.064.133t-.037.142t-.008.147t.02.145q.017.072.048.139t.074.127q.044.06.098.11t.117.089q.063.038.133.064q.069.025.142.037t.147.008t.145-.02q.072-.017.139-.048t.127-.074l2.214-1.611l5.234 7.162q-1.592.228-2.884.781Q6.75 16.763 6.75 18.5t2.505 2.811q2.192.939 5.245.939t5.245-.939q2.505-1.074 2.505-2.811t-2.505-2.811q-2.192-.939-5.245-.939q-.31 0-.612.01");
}

</style>
