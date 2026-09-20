<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsrvmmt9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vignette-2-outline-rounded" /></template>
<style>
.qsrvmmt9o {
  fill: currentColor;
  d: path("M15.75 15.74q1.539-1.528 1.539-3.74T15.75 8.25T12 6.712T8.26 8.25T6.73 12t1.53 3.74q1.529 1.53 3.74 1.53t3.75-1.53M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192M5 5v14zm3.954 10.027Q7.692 13.766 7.692 12t1.262-3.017Q10.216 7.73 11.98 7.73t3.027 1.252q1.261 1.251 1.261 3.017t-1.261 3.027t-3.027 1.262t-3.027-1.262");
}

</style>
