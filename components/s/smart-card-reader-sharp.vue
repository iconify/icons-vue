<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi5n_lb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:smart-card-reader-sharp" /></template>
<style>
.vi5n_lb7m {
  fill: currentColor;
  d: path("M3 21v-3.384h18V21zm2.827-5.27V3h12.346v12.73zm2.385-2.288h.555q.87 0 1.359-.879q.49-.879.49-2.448t-.49-2.457t-1.359-.889h-.555zm5.672-1.884q.595 0 1.019-.424q.424-.423.424-1.018t-.424-1.019t-1.018-.424t-1.019.423t-.424 1.019t.424 1.019t1.018.424");
}

</style>
