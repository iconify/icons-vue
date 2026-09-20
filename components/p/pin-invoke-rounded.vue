<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xormnub1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pin-invoke-rounded" /></template>
<style>
.xormnub1u {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h8.616q.213 0 .357.143t.143.357t-.143.357T13.23 6H4.616q-.231 0-.424.192T4 6.616v10.769q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.423v-4.616q0-.213.143-.357t.357-.143t.357.143t.143.357v4.616q0 .69-.462 1.152T19.385 19zm8.884-6.806l-3.808 3.808q-.146.146-.344.153t-.363-.159q-.16-.165-.163-.354t.163-.353l3.827-3.808H10.35q-.213 0-.357-.143t-.143-.357t.143-.357t.357-.143h3.342q.349 0 .578.23q.23.23.23.577v3.343q0 .213-.143.356t-.357.144t-.357-.143t-.143-.357zm5.077-2.348q-1.02 0-1.721-.702t-.702-1.721t.702-1.721T18.577 5t1.721.702T21 7.423t-.702 1.721t-1.721.702");
}

</style>
