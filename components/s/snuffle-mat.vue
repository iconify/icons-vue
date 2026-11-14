<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iow0-rbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:snuffle-mat" /></template>
<style>
.iow0-rbgs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.479 10.75h1.042Q9.728 7.188 12 7.188t2.479 3.562h1.042Q15.728 7.188 18 7.188q2.382 0 2.494 3.916q.432.226.804.598q.952.952.952 2.298q0 3.25-3.25 3.25H5q-3.25 0-3.25-3.25q0-1.346.952-2.298q.372-.372.804-.598Q3.618 7.188 6 7.188q2.272 0 2.479 3.562m10.5 0Q18.856 8.688 18 8.688t-.979 2.062zm-12 0Q6.856 8.688 6 8.688t-.979 2.062zM12 8.688q-.856 0-.979 2.062h1.958Q12.856 8.688 12 8.688");
}

</style>
