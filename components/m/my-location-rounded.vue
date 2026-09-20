<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkbt_1w7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:my-location-rounded" /></template>
<style>
.jkbt_1w7l {
  fill: currentColor;
  d: path("M11.5 20.95v-.961q-3.125-.293-5.16-2.328q-2.036-2.036-2.328-5.161H3.05q-.213 0-.357-.143T2.55 12t.143-.357t.357-.143h.962q.292-3.125 2.328-5.16t5.16-2.328V3.05q0-.213.143-.357T12 2.55t.357.143t.143.357v.962q3.125.292 5.16 2.328t2.329 5.16h.961q.214 0 .357.143t.143.357t-.143.357t-.357.143h-.961q-.293 3.125-2.328 5.16q-2.036 2.036-5.161 2.329v.961q0 .214-.143.357T12 21.45t-.357-.143t-.143-.357m5.45-4Q19 14.9 19 12t-2.05-4.95T12 5T7.05 7.05T5 12t2.05 4.95T12 19t4.95-2.05m-7.073-2.827Q9 13.246 9 12t.877-2.123T12 9t2.123.877T15 12t-.877 2.123T12 15t-2.123-.877");
}

</style>
