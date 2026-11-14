<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agxb_1bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:share-off" /></template>
<style>
.agxb_1bcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 5.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM5.469 9.45q-.189.077-.365.181q-.176.103-.335.232t-.297.279t-.252.32t-.202.354t-.148.38t-.09.398t-.03.406q0 .135.013.27q.013.134.04.266q.026.133.065.262q.04.13.091.254q.052.125.116.244q.063.119.138.232q.076.112.161.217q.086.104.181.2q.096.095.2.181t.217.161t.232.138q.119.064.244.116q.124.051.254.091q.129.039.262.065q.132.027.266.04q.135.013.27.013q.208 0 .413-.031q.206-.031.404-.093t.385-.153t.358-.208t.323-.26t.279-.306q.129-.163.231-.344t.176-.375m5.687 5.707q.009.123.028.245q.019.121.049.24q.031.12.071.236q.041.116.092.228t.111.219q.061.108.131.209t.149.196q.078.094.165.181q.087.088.181.167q.095.079.196.149t.208.131t.219.113q.111.051.228.092q.116.041.235.071q.119.031.241.051q.121.019.244.028M12.455 8.485L15 7m-6 6.5l1.382.806M3.5 3.5l17 17");
}

</style>
