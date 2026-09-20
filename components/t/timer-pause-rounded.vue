<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg088hb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-pause-rounded" /></template>
<style>
.hg088hb-g {
  fill: currentColor;
  d: path("M10.665 16.357q.143-.143.143-.357v-6q0-.213-.143-.357t-.357-.143t-.357.143t-.143.357v6q0 .214.143.357t.357.143t.357-.143m3.384 0q.143-.143.143-.357v-6q0-.213-.143-.357t-.357-.143t-.356.143t-.144.357v6q0 .214.144.357t.356.143t.357-.143M9.885 2.5q-.214 0-.357-.143q-.144-.144-.144-.357t.144-.357t.357-.143h4.23q.214 0 .357.143q.144.144.144.357t-.144.357q-.143.143-.356.143zm-.997 17.874q-1.455-.626-2.546-1.716t-1.716-2.545T4 13t.626-3.113t1.716-2.545t2.546-1.716T12 5q1.454 0 2.812.52t2.492 1.469l.738-.739q.14-.14.345-.15t.363.15t.16.354t-.16.354l-.738.738q.95 1.135 1.469 2.493T20 13q0 1.658-.626 3.113t-1.716 2.545t-2.546 1.716T12 21t-3.113-.626");
}

</style>
