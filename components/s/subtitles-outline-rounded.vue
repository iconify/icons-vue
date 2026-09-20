<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5wo-3bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subtitles-outline-rounded" /></template>
<style>
.b5wo-3bgz {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6zm3.077-2.577h6.846q.214 0 .357-.143t.143-.357t-.143-.357t-.357-.143H7.077q-.213 0-.357.143t-.143.357t.143.357t.357.143m3-3.577h6.846q.214 0 .357-.143q.143-.144.143-.357t-.143-.357t-.357-.143h-6.846q-.213 0-.357.143t-.143.357t.143.357t.357.143m-2.643-.143q.143-.144.143-.357t-.143-.357t-.357-.143t-.357.143t-.143.357q0 .213.143.357q.144.143.357.143t.357-.143m9.846 3.577q.143-.143.143-.357t-.143-.357t-.357-.143t-.357.143t-.143.357t.143.357t.357.143t.357-.143");
}

</style>
