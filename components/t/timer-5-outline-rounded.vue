<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btrow1_nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-5-outline-rounded" /></template>
<style>
.btrow1_nk {
  fill: currentColor;
  d: path("M13.308 16.635q.412 0 .706-.3t.294-.72V13.5q0-.402-.3-.701q-.298-.299-.7-.299h-2.616v-2.134h3.116q.212 0 .356-.144t.144-.357t-.144-.356t-.356-.143h-3.305q-.351 0-.581.232t-.23.575v2.52q0 .343.233.575t.575.232h2.808v2.135h-3.116q-.212 0-.356.144t-.144.356t.144.356t.356.144zm3.642 1.315Q19 15.9 19 13t-2.05-4.95T12 6T7.05 8.05T5 13t2.05 4.95T12 20t4.95-2.05M9.885 2.5q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h4.23q.213 0 .357.144t.144.357t-.144.356t-.356.143zm-.997 17.874q-1.455-.626-2.546-1.716t-1.716-2.545T4 13t.626-3.113t1.716-2.545t2.55-1.716T12 5q1.454 0 2.812.52t2.492 1.469l.738-.739q.14-.14.345-.15t.363.15t.16.354t-.16.354l-.738.738q.95 1.135 1.469 2.493T20 13q0 1.649-.626 3.108t-1.716 2.55t-2.546 1.716T12 21t-3.113-.626");
}

</style>
