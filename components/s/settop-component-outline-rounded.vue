<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxnvgz5_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settop-component-outline-rounded" /></template>
<style>
.pxnvgz5_v {
  fill: currentColor;
  d: path("M4.616 16q-.672 0-1.144-.472T3 14.385v-4.77q0-.67.472-1.143Q3.944 8 4.616 8h14.769q.67 0 1.143.472q.472.472.472 1.144v4.769q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h14.769q.269 0 .442-.173t.173-.442v-4.77q0-.269-.173-.442T19.385 9H4.615q-.269 0-.442.173T4 9.616v4.769q0 .269.173.442t.443.173M6 12.5h3.923q.214 0 .357-.143t.143-.357t-.143-.357t-.357-.143H6q-.213 0-.357.143T5.5 12t.143.357T6 12.5m8.578.078q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23m3 0q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23M4 15V9z");
}

</style>
