<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi87jfpmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wifi-add-rounded" /></template>
<style>
.yi87jfpmz {
  fill: currentColor;
  d: path("M18.413 19.472q-.144-.144-.144-.357v-2.5h-2.5q-.212 0-.356-.143t-.144-.357t.144-.356t.356-.143h2.5v-2.5q0-.213.144-.357q.144-.143.357-.143t.356.143t.143.357v2.5h2.5q.213 0 .357.143q.143.144.143.357t-.143.356t-.357.144h-2.5v2.5q0 .212-.144.356t-.356.144t-.356-.144m-6.933-.561q-.24-.094-.44-.294l-8.292-8.292q-.248-.248-.37-.556q-.12-.307-.12-.636q0-.367.156-.714q.157-.347.492-.592q2.008-1.398 4.318-2.112T11.997 5t4.776.715t4.317 2.107q.34.222.506.57q.166.349.166.716q0 .329-.131.649t-.379.568l-.192.192q-.135.142-.328.192t-.38-.011q-.385-.117-.795-.176t-.82-.058q-2.421 0-4.123 1.701t-1.702 4.124q0 .41.058.82t.176.795q.056.186.006.379t-.186.328q-.206.206-.446.3q-.24.093-.52.093t-.52-.094");
}

</style>
