<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhstqwb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-cluster" /></template>
<style>
.uhstqwb3l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.436 11.994l-.585-.662Q7.75 7.838 7.75 6q0-1.76 1.245-3.005T12 1.75t3.005 1.245T16.25 6q0 1.838-3.101 5.332l-.585.662q-.098.112-.232.178q-.133.066-.282.076t-.29-.038t-.254-.146q-.038-.032-.07-.07m-5.585 8.838l.585.662q.032.038.07.07q.112.099.254.146q.141.048.29.038t.282-.076q.134-.066.232-.178l.585-.662q3.101-3.494 3.101-5.332q0-1.76-1.245-3.005T7 11.25t-3.005 1.245T2.75 15.5q0 1.838 3.101 5.332m10.585.662l-.585-.662Q12.75 17.338 12.75 15.5q0-1.76 1.245-3.005T17 11.25t3.005 1.245T21.25 15.5q0 1.838-3.101 5.332l-.585.662q-.098.112-.232.178q-.133.066-.282.076t-.29-.038q-.142-.047-.254-.146q-.038-.032-.07-.07");
}

</style>
