<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-pm8cbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:orders-outline-rounded" /></template>
<style>
.m-pm8cbvc {
  fill: currentColor;
  d: path("M5 17.385V8.1L3.45 4.692q-.079-.183-.006-.387T3.7 4.02t.388-.008t.283.253L6.084 8.05h11.832l1.713-3.784q.079-.183.283-.256q.205-.073.388.011q.183.079.256.284t-.006.387L19 8.1v9.285q0 .67-.472 1.143q-.472.472-1.143.472H6.615q-.67 0-1.143-.472Q5 18.056 5 17.385m5-4.885h4q.214 0 .357-.143T14.5 12t-.143-.357T14 11.5h-4q-.213 0-.357.143T9.5 12t.143.357t.357.143M6.616 18h10.769q.269 0 .442-.173t.173-.442V9.05H6v8.335q0 .269.173.442t.443.173M6 18V9.05z");
}

</style>
