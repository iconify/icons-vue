<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7pio1qqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:page-footer-outline" /></template>
<style>
.u7pio1qqs {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm1.616-3.384q-.691 0-1.153-.463T4 15V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616V15q0 .69-.462 1.153t-1.153.463zm0-1h12.769q.269 0 .442-.174Q19 15.27 19 15V5.616q0-.27-.173-.443T18.385 5H5.615q-.269 0-.442.173T5 5.616V15q0 .27.173.442q.173.173.443.173m-.616 0V5z");
}

</style>
