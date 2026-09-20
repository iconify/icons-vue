<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzuvszbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tooltip-outline-rounded" /></template>
<style>
.dzuvszbul {
  fill: currentColor;
  d: path("M4.616 17.5q-.672 0-1.144-.472T3 15.885V4.615q0-.67.472-1.143Q3.944 3 4.616 3h14.769q.67 0 1.143.472q.472.472.472 1.144v11.269q0 .67-.472 1.143q-.472.472-1.143.472H14.29l-1.62 2.462q-.13.186-.295.28t-.376.093t-.376-.094t-.295-.28L9.709 17.5zM12 19.189l1.754-2.689h5.63q.27 0 .443-.173t.173-.442V4.615q0-.269-.173-.442T19.385 4H4.615q-.269 0-.442.173T4 4.616v11.269q0 .269.173.442t.443.173h5.63zm0-8.939");
}

</style>
