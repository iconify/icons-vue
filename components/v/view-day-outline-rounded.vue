<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojtf7acau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-day-outline-rounded" /></template>
<style>
.ojtf7acau {
  fill: currentColor;
  d: path("M4.475 18.77q-.194 0-.334-.144Q4 18.483 4 18.269t.143-.356t.357-.144h15.025q.194 0 .335.144q.14.143.14.356t-.143.357t-.357.143zm0-12.54q-.194 0-.334-.143T4 5.731t.143-.357t.357-.143h15.025q.194 0 .335.143q.14.143.14.357t-.143.356t-.357.144zM5.615 15q-.67 0-1.143-.472Q4 14.056 4 13.385v-2.77q0-.67.472-1.143Q4.944 9 5.616 9h12.769q.67 0 1.143.472q.472.472.472 1.144v2.769q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h12.77q.269 0 .442-.173t.173-.442v-2.77q0-.269-.173-.442T18.385 10H5.615q-.269 0-.442.173T5 10.616v2.769q0 .269.173.442t.443.173M5 10h.616q-.27 0-.443.173T5 10.616v2.769q0 .269.173.442t.443.173H5z");
}

</style>
