<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkch2vbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pin-invoke-outline-sharp" /></template>
<style>
.bkch2vbzi {
  fill: currentColor;
  d: path("M3 19V5h10.73v1H4v12h16v-5.73h1V19zm6.339-2.644l-.708-.714l4.18-4.161H9.85v-1h4.65v4.65h-1v-2.937zm9.238-6.51q-1.01 0-1.717-.706t-.706-1.717t.706-1.716T18.577 5t1.716.707T21 7.423t-.707 1.717t-1.716.706");
}

</style>
