<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkk7vcbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-backup-restore-outline-rounded" /></template>
<style>
.vkk7vcbeo {
  fill: currentColor;
  d: path("M11.962 20q-2.881 0-5.066-1.778T4.141 13.7q-.062-.221.063-.409t.338-.218q.208-.03.37.093q.161.123.229.35q.542 2.384 2.446 3.934T11.962 19q2.925 0 4.962-2.037T18.962 12t-2.038-4.963T11.962 5q-1.553 0-2.918.656q-1.365.655-2.41 1.805h1.981q.214 0 .357.144q.143.143.143.356t-.143.357t-.357.143H5.77q-.348 0-.578-.23q-.23-.229-.23-.577V4.808q0-.214.144-.357t.357-.143t.356.143t.144.357v1.888q1.16-1.273 2.718-1.984T11.962 4q1.663 0 3.118.626t2.542 1.714t1.714 2.542t.626 3.118t-.626 3.118t-1.714 2.542t-2.542 1.714t-3.118.626m0-7q-.402 0-.701-.299t-.3-.701t.3-.701t.7-.299t.702.299t.299.701t-.3.701t-.7.299");
}

</style>
