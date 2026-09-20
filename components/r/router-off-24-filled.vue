<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atri2ddlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:router-off-24-filled" /></template>
<style>
.atri2ddlv {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-.633-.633A2.98 2.98 0 0 1 18 22H6a3 3 0 1 1 0-6h5.25v-2.095a3 3 0 0 1-2.134-3.728L7.96 9.02A4.5 4.5 0 0 0 7.5 11v.25a.75.75 0 0 1-1.5 0V11c0-1.129.312-2.184.854-3.085L5.768 6.828A7.47 7.47 0 0 0 4.5 11v.25a.75.75 0 0 1-1.5 0V11c0-1.96.626-3.772 1.69-5.25L2.22 3.28a.75.75 0 0 1 0-1.06m10.53 11.685V16h2.19l-2.118-2.117q-.035.012-.072.022M12 5a6 6 0 0 1 6 6v.25a.75.75 0 0 1-1.5 0V11a4.5 4.5 0 0 0-6.4-4.081l-1.11-1.11A5.97 5.97 0 0 1 12 5m0-3a9 9 0 0 1 9 9v.25a.75.75 0 0 1-1.5 0V11A7.5 7.5 0 0 0 7.901 4.72L6.822 3.64A8.96 8.96 0 0 1 12 2m0 6a3 3 0 0 1 2.91 3.727l-3.637-3.635A3 3 0 0 1 12 8");
}

</style>
