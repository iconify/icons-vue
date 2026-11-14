<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g64hzdbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pitcher-plant" /></template>
<style>
.g64hzdbpn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.75 7.5q0-.046-.002-.091Q22.25 6.677 22.25 2.5q0-.068-.012-.135t-.037-.13t-.059-.122t-.08-.109t-.098-.093q-.054-.042-.114-.074t-.125-.052t-.132-.029q-4.241-.53-6.015 3.73Q14.538 5.25 13 5.25q-4.75 0-4.75 2.25v8q0 1.968 1.391 3.359q.837.836 1.881 1.17q-.986.625-2.911.708Q7.538 16.25 2.5 16.25q-.062 0-.123.01q-.147.025-.274.104t-.213.2t-.121.267q-.033.145-.009.292Q2.615 22.25 8 22.25q4.08 0 5.44-2.018q1.686-.14 2.919-1.373q1.391-1.391 1.391-3.359zm2.946-4.297q-2.504.038-3.702 2.794q3.305-.355 3.702-2.794M9.75 9.318q1.169.432 3.25.432t3.25-.432V15.5q0 3.25-3.25 3.25T9.75 15.5z");
}

</style>
