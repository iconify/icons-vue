<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx52d5bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-signin-outline-rounded" /></template>
<style>
.qx52d5bwx {
  fill: currentColor;
  d: path("M4.616 18q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v10.769q0 .69-.463 1.153T19.385 18H15v1.192q0 .349-.23.578t-.578.23H9.808q-.348 0-.578-.23T9 19.192V18zm0-1h14.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T19.385 5H4.615q-.23 0-.423.192T4 5.616v10.769q0 .23.192.423t.423.192M4 17V5zm4.692-2.692h6.616v-.166q0-.875-.88-1.354q-.878-.48-2.428-.48t-2.429.48t-.879 1.354zm4.374-4.05q.434-.433.434-1.066t-.434-1.066q-.433-.434-1.066-.434t-1.066.434t-.434 1.066t.434 1.067q.433.433 1.066.433t1.066-.433");
}

</style>
