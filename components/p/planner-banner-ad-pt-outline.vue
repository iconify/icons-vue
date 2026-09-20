<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo1krnbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:planner-banner-ad-pt-outline" /></template>
<style>
.fo1krnbvs {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.769q.69 0 1.153.463T19 4.616v14.769q0 .69-.462 1.153T17.384 21zm0-1h10.769q.23 0 .423-.192t.192-.424V4.616q0-.231-.192-.424T17.384 4H6.616q-.231 0-.424.192T6 4.615v14.77q0 .23.192.423t.423.192m1.116-2.5h8.692l-2.757-3.654l-2.454 3.077l-1.589-1.884zM6 20V4z");
}

</style>
