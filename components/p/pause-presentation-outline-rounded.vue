<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w84j5bcap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pause-presentation-outline-rounded" /></template>
<style>
.w84j5bcap {
  fill: currentColor;
  d: path("M10.665 15.357q.143-.143.143-.357V9q0-.213-.143-.357t-.357-.143t-.357.143T9.808 9v6q0 .214.143.357t.357.143t.357-.143m3.384 0q.143-.143.143-.357V9q0-.213-.143-.357t-.357-.143t-.356.143t-.144.357v6q0 .214.144.357t.356.143t.357-.143M4.616 19q-.691 0-1.154-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6z");
}

</style>
