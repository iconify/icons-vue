<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y916bgs6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-paste-outline" /></template>
<style>
.y916bgs6l {
  fill: currentColor;
  d: path("M12.846 20v-5.884q0-.672.472-1.144q.473-.472 1.144-.472h4.923q.67 0 1.143.472q.472.472.472 1.144V20h-1v-6.038q0-.193-.134-.327q-.135-.135-.327-.135h-2.116V18h-1v-4.5h-2.115q-.193 0-.327.135q-.135.134-.135.326V20zm-7.23 0q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h4.636q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985h4.63q.672 0 1.144.472T20 5.616v4.5h-1v-4.5q0-.231-.192-.424T18.384 5H16v2.23H8V5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192h4.847v1zm6.962-14.999q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23");
}

</style>
