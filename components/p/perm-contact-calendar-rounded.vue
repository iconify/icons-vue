<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i30iccb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:perm-contact-calendar-rounded" /></template>
<style>
.i30iccb0z {
  fill: currentColor;
  d: path("M5 19.12q1.35-1.326 3.138-2.088T12 16.269t3.863.763T19 19.119V6.616q0-.231-.192-.424T18.384 6H5.616q-.231 0-.424.192T5 6.616zm4.871-6.491Q9 11.758 9 10.5t.871-2.129T12 7.5t2.129.871T15 10.5t-.871 2.129T12 13.5t-2.129-.871M5.616 21q-.691 0-1.153-.462T4 19.385V6.615q0-.69.463-1.152T5.616 5h1.769V3.308q0-.233.153-.386t.385-.153t.386.153t.153.386V5h7.154V3.27q0-.214.143-.358t.357-.143t.356.143t.144.357V5h1.769q.69 0 1.153.463T20 6.616v12.769q0 .69-.462 1.153T18.384 21z");
}

</style>
