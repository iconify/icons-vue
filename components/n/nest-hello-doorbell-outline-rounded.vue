<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x060z8bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-hello-doorbell-outline-rounded" /></template>
<style>
.x060z8bcd {
  fill: currentColor;
  d: path("M8.818 20.184Q7.5 18.868 7.5 17V7q0-1.868 1.316-3.184Q10.13 2.5 11.997 2.5t3.185 1.316T16.5 7v10q0 1.868-1.315 3.184q-1.316 1.316-3.182 1.316t-3.185-1.316m5.663-.705Q15.5 18.46 15.5 17V7q0-1.458-1.022-2.48q-1.021-1.02-2.48-1.02T9.519 4.52T8.5 7v10q0 1.458 1.022 2.48q1.021 1.02 2.48 1.02t2.479-1.02M13.336 9.33q.548-.553.548-1.331t-.549-1.331T12 6.116t-1.336.553T10.117 8t.549 1.331T12 9.885t1.336-.554m0 8q.548-.553.548-1.331t-.549-1.331T12 14.116t-1.336.553T10.117 16t.549 1.331t1.335.553t1.336-.553m-2.126-.541q-.326-.326-.326-.79t.326-.79t.79-.325t.79.326t.326.789t-.326.79t-.79.326t-.79-.326");
}

</style>
