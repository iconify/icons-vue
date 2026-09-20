<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d13ld_bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:smart-card-reader-outline-sharp" /></template>
<style>
.d13ld_bqi {
  fill: currentColor;
  d: path("M3 21v-3.384h18V21zm1-1h16v-1.384H4zm1.827-4.27V3h12.346v12.73h-1V4H6.827v11.73zm2.385-2.288h.555q.87 0 1.359-.879q.49-.879.49-2.448t-.49-2.457t-1.359-.889h-.555zm5.672-1.884q.595 0 1.019-.424q.424-.423.424-1.018t-.424-1.019t-1.018-.424t-1.019.423t-.424 1.019t.424 1.019t1.018.424M12 9.866");
}

</style>
