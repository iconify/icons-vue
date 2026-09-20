<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umh9y9bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-drinks-rounded" /></template>
<style>
.umh9y9bbq {
  fill: currentColor;
  d: path("M14.07 11.258L9.811 7h6.738l1.8-2H7.811l-1-1h11.037q.54 0 .879.38t.339.836q0 .213-.081.413t-.243.39zM7.5 20.5q-.213 0-.357-.143T7 20t.143-.357t.357-.143h4v-6.579l-8.4-8.4q-.14-.14-.15-.341t.15-.366q.165-.166.357-.166t.356.166l16.38 16.378q.145.147.155.345t-.156.363q-.165.166-.356.166q-.192 0-.357-.166l-6.973-6.973L12.5 19.5h4q.214 0 .357.143T17 20t-.143.357t-.357.143z");
}

</style>
