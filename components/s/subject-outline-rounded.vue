<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd_89ellp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subject-outline-rounded" /></template>
<style>
.zd_89ellp {
  fill: currentColor;
  d: path("M5.616 18.212q-.262 0-.439-.171T5 17.617t.177-.435t.439-.182H12.5q.213 0 .356.15t.144.37q0 .212-.143.356t-.338.143zM5.5 14.327q-.213 0-.356-.144T5 13.826t.144-.356t.356-.143h13q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.143zm0-3.654q-.213 0-.356-.144Q5 10.385 5 10.173q0-.213.144-.357t.356-.143h13q.213 0 .356.144t.144.357t-.144.356t-.356.143zM5.616 7q-.262 0-.439-.182Q5 6.637 5 6.385t.177-.434t.439-.182h12.769q.261 0 .438.182t.177.434t-.177.433t-.438.182z");
}

</style>
