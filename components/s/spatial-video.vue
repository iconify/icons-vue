<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd1q9cbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:spatial-video" /></template>
<style>
.fd1q9cbto {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.19 15.25q-.214 1.284-1.185 2.255Q15.76 18.75 14 18.75H6q-1.76 0-3.005-1.245T1.75 14.5v-4q0-1.76 1.245-3.005q.971-.971 2.255-1.185V6q0-2.75 2.75-2.75h11.5q2.75 0 2.75 2.75v6.5q0 2.75-2.75 2.75zm-11.44-9V6q0-1.25 1.25-1.25h11.5q1.25 0 1.25 1.25v6.5q0 1.25-1.25 1.25h-1.25V10.5q0-1.76-1.245-3.005T14 6.25zm3.835 4.066q-1.124-.619-2.229.034T7.25 12.287v.426q0 1.284 1.105 1.937t2.23.034l.387-.213q1.165-.641 1.165-1.971t-1.165-1.971z");
}

</style>
