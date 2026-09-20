<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlm00dbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-system-daydream-rounded" /></template>
<style>
.tlm00dbib {
  fill: currentColor;
  d: path("M9.154 14.904h6.5q.627 0 1.063-.437t.437-1.063t-.437-1.063t-1.063-.437h-.512q-.046-1.217-.814-2.109t-1.947-.891q-.973 0-1.748.544t-1.014 1.456h-.528q-.83 0-1.383.582q-.554.583-.554 1.418q0 .846.577 1.423t1.423.577M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
