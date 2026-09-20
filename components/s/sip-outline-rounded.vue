<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="degi-zbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sip-outline-rounded" /></template>
<style>
.degi-zbow {
  fill: currentColor;
  d: path("M12.357 14.549q.143-.143.143-.357V9.808q0-.214-.143-.357T12 9.308t-.357.143t-.143.357v4.384q0 .214.143.357t.357.143t.357-.143m2.71.017q.125-.125.125-.316v-1.558h2.731q.329 0 .549-.22t.22-.549v-1.846q0-.329-.22-.549t-.549-.22h-3.211q-.162 0-.283.12q-.121.122-.121.284v4.538q0 .19.126.316t.316.126t.316-.126m-9.316.126h3.173q.329 0 .549-.22t.22-.549v-1.596q0-.329-.22-.549t-.549-.22h-2.73v-1.366H9.25q.19 0 .316-.126q.126-.125.126-.316t-.126-.316t-.316-.126H6.077q-.329 0-.549.22t-.22.549v1.596q0 .329.22.549t.549.22h2.73v1.366H5.75q-.19 0-.316.126t-.126.316t.126.316t.316.126m9.442-2.884v-1.616h2.616v1.616zM4.615 19q-.69 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.77q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6z");
}

</style>
