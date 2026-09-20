<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnn5u1bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:swipe-left-alt-rounded" /></template>
<style>
.cnn5u1bia {
  fill: currentColor;
  d: path("M15 17q-1.825 0-3.187-1.137T10.1 13H5.825l.9.9q.275.275.275.688t-.3.712q-.275.275-.7.275t-.7-.275l-2.6-2.6q-.15-.15-.213-.325T2.426 12t.063-.375t.212-.325l2.6-2.6q.275-.275.688-.275T6.7 8.7q.3.3.3.713t-.3.712L5.825 11H10.1q.35-1.725 1.713-2.863T15 7q2.075 0 3.538 1.463T20 12t-1.463 3.538T15 17");
}

</style>
