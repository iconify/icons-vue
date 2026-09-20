<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-f702brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:page-info-outline-rounded" /></template>
<style>
.g-f702brd {
  fill: currentColor;
  d: path("M15.472 18.201q-.856-.857-.856-2.085q0-1.23.856-2.086q.857-.857 2.086-.857t2.085.857t.857 2.086t-.857 2.085t-2.085.857q-1.23 0-2.086-.857m3.458-.711q.57-.569.57-1.373q0-.803-.568-1.374t-1.372-.57t-1.374.568q-.57.569-.57 1.373q0 .803.568 1.374t1.372.57t1.374-.568m-7.2-.874H5.5q-.213 0-.356-.144T5 16.115t.144-.356t.356-.143h6.23q.213 0 .357.143q.144.144.144.357t-.144.356t-.356.144M4.357 9.97Q3.5 9.113 3.5 7.884T4.357 5.8t2.085-.857q1.23 0 2.086.857q.857.857.857 2.085q0 1.23-.857 2.086q-.857.857-2.086.857T4.357 9.97m3.458-.711q.57-.569.57-1.373q0-.803-.569-1.374t-1.372-.57t-1.374.568t-.57 1.373t.568 1.374t1.372.57q.804 0 1.374-.568M18.5 8.385h-6.23q-.213 0-.357-.144t-.144-.357t.144-.356t.356-.143H18.5q.213 0 .356.144t.144.356t-.144.356t-.356.144m-12.058-.5");
}

</style>
