<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayhgm3b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:star" /></template>
<style>
.ayhgm3b5d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.001 5.735l.001.001l.97 2.059q.176.372.584.424l2.26.288q1.391.176 1.825 1.51t-.588 2.295l-1.66 1.561q-.3.282-.223.686l.425 2.238q.262 1.378-.873 2.202q-1.134.825-2.363.151l-1.998-1.097q-.361-.198-.722 0l-1.997 1.096q-1.23.675-2.364-.15q-1.135-.824-.873-2.202l.425-2.238q.077-.404-.223-.686l-1.66-1.561q-1.021-.961-.588-2.295q.434-1.334 1.826-1.51l2.258-.288q.409-.052.585-.424l.971-2.06q.597-1.27 2.001-1.27t2.001 1.27");
}

</style>
