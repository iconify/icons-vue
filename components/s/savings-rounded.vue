<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfuvjhb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:savings-rounded" /></template>
<style>
.hfuvjhb1y {
  fill: currentColor;
  d: path("M6.483 20q-.517 0-.968-.342t-.588-.84q-.625-2.216-.996-3.677q-.372-1.46-.58-2.469q-.209-1.009-.28-1.726T3 9.5q0-1.877 1.312-3.189T7.5 5H13q.675-.9 1.588-1.45T16.5 3q.202 0 .351.149T17 3.5q0 .054-.018.098t-.03.112q-.12.313-.236.723t-.243 1.138L19.402 8.5h.79q.349 0 .578.23t.23.578v3.846q0 .267-.149.479t-.417.298l-2.067.68l-1.269 4.233q-.161.535-.59.845q-.43.311-.97.311h-.923q-.67 0-1.143-.472Q13 19.056 13 18.385V18H9v.385q0 .67-.472 1.143Q8.056 20 7.384 20zm10.057-9.46q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23M12.5 8.5q.214 0 .357-.143T13 8t-.143-.357T12.5 7.5h-4q-.213 0-.357.143T8 8t.143.357t.357.143z");
}

</style>
