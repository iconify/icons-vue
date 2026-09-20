<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dn2eezbnd"/><path class="jlnq_q0_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-sweep-24-regular" /></template>
<style>
.dn2eezbnd {
  d: path("M3.142 5.75A2.75 2.75 0 0 1 5.892 3h12.5a2.75 2.75 0 0 1 2.75 2.75v6.365a6.473 6.473 0 0 0-1.5-.754V5.75c0-.69-.56-1.25-1.25-1.25h-12.5c-.69 0-1.25.56-1.25 1.25v12.5c0 .69.56 1.25 1.25 1.25h5.421c.173.534.412 1.037.709 1.5h-6.13a2.75 2.75 0 0 1-2.75-2.75V5.75z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.jlnq_q0_l {
  d: path("M23 17.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0zm-5.646-2.146a.5.5 0 0 0-.708-.708l-2.5 2.5a.5.5 0 0 0 0 .708l2.5 2.5a.5.5 0 0 0 .708-.708L15.707 18H20.5a.5.5 0 0 0 0-1h-4.793l1.647-1.646z");
  fill: currentColor;
}

</style>
