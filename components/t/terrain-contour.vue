<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kri2wzbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:terrain-contour" /></template>
<style>
.kri2wzbrq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q4.471 0 7.286 2.294Q22.25 6.458 22.25 10.5q0 4.612-2.335 7.759Q17.325 21.75 13 21.75q-2.308 0-4.936-2.235q-1.681-1.43-2.801-1.803l-.042-.016Q1.75 16.308 1.75 11q0-4.073 2.939-6.686Q7.574 1.75 12 1.75M19 11q0-5.75-6.5-5.75q-3.091 0-5.109 1.527Q5.25 8.397 5.25 11q0 2.964 2.415 4.171l.03.014q.858.382 2.09 1.476Q11.572 18.25 13 18.25q6 0 6-7.25");
}

</style>
