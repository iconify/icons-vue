<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq_wzwbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:soundbar-rounded" /></template>
<style>
.tq_wzwbwi {
  fill: currentColor;
  d: path("M11.643 9.836q-.143.144-.143.356v1.904q0 .204.144.343t.357.138t.356-.144t.143-.356v-1.885q0-.212-.144-.356t-.357-.144t-.356.144m-2.787 8.02Q8.713 18 8.5 18H6.27q-.213 0-.357-.144t-.144-.357t.144-.356t.356-.143H8.5q.213 0 .356.144t.144.357t-.144.356m9.231 0q-.144.143-.356.143h-2.25q-.204 0-.343-.144T15 17.499t.144-.356T15.5 17h2.23q.213 0 .357.144t.144.357t-.144.356m-10.818-5.28q.614 0 1.028-.414q.414-.415.414-1.019t-.414-1.018t-1.018-.414t-1.028.417t-.424 1.005q0 .614.423 1.028q.424.415 1.02.415m9.455.02q.6 0 1.034-.428q.433-.428.433-1.028t-.431-1.025t-1.038-.424t-1.03.424t-.424 1.025t.428 1.028t1.028.427M4.615 15.27q-.69 0-1.152-.462T3 13.652V8.617q0-.692.463-1.155T4.615 7h14.77q.69 0 1.152.463T21 8.617v5.035q0 .692-.463 1.155t-1.153.462z");
}

</style>
