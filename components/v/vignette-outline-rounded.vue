<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w25ga2idu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vignette-outline-rounded" /></template>
<style>
.w25ga2idu {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6zm11.879-3.543Q17.5 13.413 17.5 12t-1.621-2.457Q14.258 8.5 12 8.5T8.121 9.543T6.5 12t1.621 2.457T12 15.5t3.879-1.043m-7.038-.701Q7.5 13.012 7.5 12t1.341-1.756T12 9.5t3.159.744T16.5 12t-1.341 1.756T12 14.5t-3.159-.744");
}

</style>
