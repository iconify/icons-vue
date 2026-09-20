<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dscceztum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-add-outline-rounded" /></template>
<style>
.dscceztum {
  fill: currentColor;
  d: path("M18.25 10.5h-2.5q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.143h2.5V7q0-.213.144-.356t.357-.144t.356.144t.143.356v2.5h2.5q.213 0 .356.144t.144.357t-.144.356t-.356.143h-2.5V13q0 .213-.144.356t-.357.144t-.356-.144T18.25 13zm-11.373.008Q6 9.63 6 8.385t.877-2.123T9 5.385t2.123.877T12 8.385t-.877 2.123T9 11.385t-2.123-.877M2 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v.608q0 .44-.299.74q-.299.298-.74.298H3.04q-.441 0-.74-.299t-.3-.739m1 .039h12v-.647q0-.332-.215-.625q-.214-.292-.593-.494q-1.234-.598-2.545-.916T9 14.616t-2.646.318t-2.546.916q-.38.202-.593.494Q3 16.637 3 16.97zm7.413-7.819Q11 9.21 11 8.385t-.587-1.413T9 6.385t-1.412.587T7 8.385t.588 1.412T9 10.385t1.413-.588M9 17.616");
}

</style>
