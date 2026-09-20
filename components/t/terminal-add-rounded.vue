<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxw8p3bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:terminal-add-rounded" /></template>
<style>
.cxw8p3bib {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5H11.9q.298 0 .51.217q.211.218.205.516q.02.32.063.661q.043.34.135.656q.106.367-.093.659q-.199.291-.547.291H4v9.385q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.423v-5.893q0-.213.143-.357t.357-.143t.357.143t.143.357v5.893q0 .69-.462 1.153T19.385 19zM18 6h-2.5q-.213 0-.357-.143T15 5.5t.143-.357T15.5 5H18V2.5q0-.213.143-.357T18.5 2t.357.143T19 2.5V5h2.5q.214 0 .357.143T22 5.5t-.143.357T21.5 6H19v2.5q0 .214-.143.357T18.5 9t-.357-.143T18 8.5zm-5 10.5q-.213 0-.357-.143T12.5 16t.143-.357T13 15.5h4q.214 0 .357.143T17.5 16t-.143.357T17 16.5zM9.387 13L7.14 10.754q-.146-.146-.153-.354t.16-.354q.145-.14.353-.133t.354.153l2.369 2.369q.242.242.242.565t-.242.566l-2.389 2.388q-.14.14-.34.134t-.348-.153q-.14-.14-.14-.335t.14-.334z");
}

</style>
