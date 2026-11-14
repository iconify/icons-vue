<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejc55fbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-care-hotel" /></template>
<style>
.ejc55fbee {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 3.5q2.815 0 3.192 2.25h7.616Q16.185 3.5 19 3.5q3.25 0 3.25 3q0 .823-.745 1.654q-.255.285-.255.346t.255.346q.745.831.745 1.654q0 1.962-1.39 2.641Q20.25 13 19.5 13q-.832 0-1.5.291q-.495-.216-1.081-.272q-.908-.559-1.111-1.769H8.192Q7.815 13.5 5 13.5q-3.25 0-3.25-3q0-.823.745-1.654q.255-.285.255-.346t-.255-.346Q1.75 7.323 1.75 6.5q0-3 3.25-3m12.57 18.364Q13.75 19.19 13.75 17q0-2.75 2.75-2.75q.89 0 1.5.523q.61-.523 1.5-.523q2.75 0 2.75 2.75q0 2.19-3.82 4.864q-.094.067-.205.101Q18.115 22 18 22t-.225-.035q-.111-.034-.205-.101M20.75 17q0 1.311-2.75 3.328q-2.75-2.017-2.75-3.328q0-1.25 1.25-1.25q.536 0 .829.585q.067.134.18.232q.112.097.254.145q.141.047.29.036q.149-.01.282-.077q.109-.055.195-.141t.141-.195q.293-.585.829-.585q1.25 0 1.25 1.25");
}

</style>
