<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkdk_z2ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:video-viewing" /></template>
<style>
.dkdk_z2ze {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 2.75H6q-1.76 0-3.005 1.245T1.75 7v2.5q0 1.76 1.245 3.005T6 13.75h5.5q1.76 0 3.005-1.245q.659-.659.969-1.462q.041.021.083.04l3.499 1.616q1.119.516 2.157-.147q1.037-.664 1.037-1.896V5.844q0-1.232-1.037-1.896q-1.038-.663-2.156-.147l-3.5 1.616h-.001l-.082.04q-.31-.803-.969-1.462Q13.26 2.75 11.5 2.75m2.715 14.257v-.001l2.25-2.099q1.535-1.431 3.07-.001l2.25 2.101q.715.667.715 1.645v1.598q0 2.25-2.25 2.25h-4.5q-2.25 0-2.25-2.25v-1.598q0-.978.715-1.645m1.024 1.097q-.239.222-.239.548v1.598q0 .75.75.75h4.5q.75 0 .75-.75v-1.598q0-.326-.239-.549l-2.25-2.099q-.511-.477-1.022-.001z");
}

</style>
