<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7zzukb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mail" /></template>
<style>
.p7zzukb2y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 4.25h-11q-1.76 0-3.005 1.245T2.25 8.5v7q0 1.76 1.245 3.005T6.5 19.75h11q1.76 0 3.005-1.245T21.75 15.5v-7q0-1.76-1.245-3.005T17.5 4.25M12 11.585l4.57-3.199q.06-.043.128-.073t.14-.045t.146-.018q.074-.001.146.011q.073.013.142.04t.131.067t.116.09t.095.112q.086.122.118.268q.033.145.007.292t-.107.273q-.08.126-.202.211l-5 3.5q-.094.067-.205.101q-.11.035-.225.035t-.225-.035q-.111-.034-.205-.101l-5-3.5q-.061-.042-.112-.095q-.051-.054-.09-.116q-.04-.062-.067-.131t-.04-.142q-.012-.072-.011-.146t.018-.146q.016-.072.045-.14q.03-.068.073-.128q.042-.061.095-.112q.054-.051.116-.09q.062-.04.131-.067t.142-.04q.072-.012.146-.011t.146.018t.14.045q.068.03.128.073z");
}

</style>
