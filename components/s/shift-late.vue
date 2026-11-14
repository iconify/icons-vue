<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ibs3xeb7r"/><path class="i8578ibva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shift-late" /></template>
<style>
.i8578ibva {
  d: path("M6.5 18.5q0-.147.014-.294t.044-.291q.028-.145.071-.286t.099-.277q.057-.136.126-.266q.07-.13.152-.253q.081-.122.175-.236t.198-.218t.218-.198t.236-.175q.123-.082.253-.152t.266-.126t.277-.099t.286-.071t.291-.044t.294-.014q.215 0 .428.031q.214.031.42.091q.207.061.402.151t.377.207q.181.116.343.258q.163.141.303.304q.141.163.256.345t.205.378M4.75 18.5h6.3M9.5 12.75V14m-3.75.5l.75.75m6.75-.75l-.75.75m5.5-.75v7m-3-3l3 3l3-3");
}

.ibs3xeb7r {
  d: path("M14.1 21.5H3v-17h18v10.1M8 2.5v4m8-4v4m-13 3h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
