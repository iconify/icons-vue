<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljj7rlv5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-5-rounded" /></template>
<style>
.ljj7rlv5v {
  fill: currentColor;
  d: path("M13.308 16.635q.42 0 .71-.3t.29-.72V13.5q0-.402-.3-.701q-.298-.299-.7-.299h-2.616v-2.134h3.116q.213 0 .357-.144q.143-.143.143-.356q0-.214-.143-.357t-.357-.143H10.5q-.348 0-.578.23q-.23.229-.23.577v2.52q0 .348.23.577q.23.23.578.23h2.808v2.135h-3.116q-.213 0-.356.143q-.144.143-.144.357q0 .213.144.356t.356.144zM9.885 2.5q-.214 0-.357-.143q-.144-.144-.144-.357t.144-.357t.357-.143h4.23q.214 0 .357.143q.144.144.144.357t-.144.357q-.143.143-.356.143zm-.997 17.874q-1.455-.626-2.546-1.716t-1.716-2.545T4 13t.626-3.113t1.716-2.545t2.546-1.716T12 5q1.454 0 2.812.52t2.492 1.469l.738-.739q.14-.14.345-.15t.363.15t.16.354t-.16.354l-.738.738q.95 1.135 1.469 2.493T20 13q0 1.658-.626 3.113t-1.716 2.545t-2.546 1.716T12 21t-3.113-.626");
}

</style>
