<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-33yjbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rowing-outline-rounded" /></template>
<style>
.e-33yjbbc {
  fill: currentColor;
  d: path("m17.512 22.666l-1.693-1.693q-.13-.13-.186-.27t-.056-.301v-1.171l-7.408-7.408q-.225.05-.392.075l-.43.064v-1.047q1.192-.103 2.684-.883t2.196-1.54l1.323-1.396q.229-.298.56-.447t.717-.149q.662 0 1.129.467t.467 1.13V14q0 .708-.305 1.245t-.768.867l-2.273-2.262V9.07q-.904.886-1.873 1.476q-.97.59-1.927.923l7.03 7.031h1.172q.161 0 .3.056q.14.055.271.186l1.692 1.692q.242.243.242.566t-.242.566l-1.1 1.1q-.242.242-.565.242t-.566-.243M8.808 16.5l-2.942 2.942q-.172.172-.404.172t-.404-.172t-.171-.403t.17-.404l4.232-4.231l2.096 2.096zm5.126-11.664q-.434-.434-.434-1.067t.434-1.066T15 2.269t1.066.434t.434 1.066t-.434 1.067q-.433.433-1.066.433t-1.066-.433M6.975 11.81q-.152-.152-.152-.372t.152-.37t.371-.153t.371.152t.152.371t-.152.371q-.151.153-.37.153t-.372-.152");
}

</style>
