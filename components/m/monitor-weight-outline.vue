<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsoppkhcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitor-weight-outline" /></template>
<style>
.lsoppkhcd {
  fill: currentColor;
  d: path("M12 11.616q1.096 0 1.856-.76T14.616 9t-.76-1.856T12 6.384t-1.856.76T9.384 9t.76 1.856t1.856.76M10.15 9.35Q10 9.2 10 9t.15-.35t.35-.15t.35.15T11 9t-.15.35t-.35.15t-.35-.15m1.5 0Q11.5 9.2 11.5 9t.15-.35t.35-.15t.35.15t.15.35t-.15.35t-.35.15t-.35-.15m1.5 0Q13 9.2 13 9t.15-.35t.35-.15t.35.15T14 9t-.15.35t-.35.15t-.35-.15M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192M5 5v14z");
}

</style>
