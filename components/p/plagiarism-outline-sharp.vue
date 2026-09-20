<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs72ombhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:plagiarism-outline-sharp" /></template>
<style>
.vs72ombhy {
  fill: currentColor;
  d: path("M11.066 15.923q.488 0 .935-.151q.447-.15.841-.414l2.72 2.719l.707-.708l-2.719-2.719q.302-.375.434-.832t.132-.945q0-1.238-.872-2.094t-2.128-.856t-2.13.871q-.87.871-.87 2.129t.855 2.129t2.095.871m-1.36-1.591q-.59-.592-.59-1.409t.59-1.408t1.41-.592t1.408.592q.592.59.592 1.408t-.592 1.409t-1.408.591q-.818 0-1.41-.591M5 21V3h9.5L19 7.5V21zm9-13V4H6v16h12V8zM6 4v4zv16z");
}

</style>
