<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1h9_e-yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:workflow-support" /></template>
<style>
.k1h9_e-yh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.25H5q-1.346 0-2.298.952T1.75 5.5q0 3.25 3.25 3.25v5.5q-1.346 0-2.298.952T1.75 17.5q0 3.25 3.25 3.25h1.5q3.25 0 3.25-3.25T6.5 14.25v-5.5q2.85 0 3.201-2.5h4.598q.351 2.5 3.201 2.5H19q3.25 0 3.25-3.25q0-1.346-.952-2.298T19 2.25h-1.5q-2.85 0-3.201 2.5H9.701Q9.35 2.25 6.5 2.25m7.279 15.095Q14.092 14 17.75 14q1.657 0 2.828 1.172q.931.93 1.122 2.167q1.05.306 1.05 1.661v1.5q0 1.75-1.75 1.75t-1.75-1.75V19q0-1.274.928-1.621q-.158-.645-.66-1.147q-.732-.732-1.768-.732q-2.162 0-2.454 1.87q.954.338.954 1.63v1.5q0 1.75-1.75 1.75t-1.75-1.75V19q0-1.342 1.029-1.655m.721 1.405q-.25 0-.25.25v1.5q0 .25.25.25t.25-.25V19q0-.25-.25-.25m6.25.25q0-.25.25-.25t.25.25v1.5q0 .25-.25.25t-.25-.25z");
}

</style>
