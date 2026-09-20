<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2x8qs_on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:watch-lock-outline" /></template>
<style>
.o2x8qs_on {
  fill: currentColor;
  d: path("M10.73 14.462q-.366 0-.606-.24t-.24-.606V11.5q0-.348.24-.597q.24-.25.607-.25v-.845q0-.53.37-.9t.899-.37t.899.37t.37.9v.846q.348 0 .597.249q.25.249.25.597v2.116q0 .367-.25.606q-.249.24-.597.24zm.741-3.808h1.058v-.846q0-.217-.156-.373T12 9.279t-.373.156t-.156.373zM10.731 4h2.538zm0 16h2.538zm-.77 1l-1.119-3.934q-1.258-.739-2.05-2.087T6 12t.792-2.979t2.05-2.087L9.962 3h4.077l1.119 3.935q1.258.738 2.05 2.086T18 12t-.792 2.979t-2.05 2.087L14.038 21zm5.577-5.462Q17 14.075 17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17t3.538-1.463m-5.476-9.21q.519-.163.991-.248T12 5.994t.947.085t.991.248L13.27 4h-2.538zM10.73 20h2.538l.67-2.327q-.52.164-.992.236T12 17.98t-.947-.072t-.991-.236z");
}

</style>
