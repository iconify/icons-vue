<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0r22kbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-lock-sharp" /></template>
<style>
.p0r22kbry {
  fill: currentColor;
  d: path("M16 21v-5h1v-1q0-.825.588-1.412T19 13t1.413.588T21 15v1h1v5zm2-5h2v-1q0-.425-.288-.712T19 14t-.712.288T18 15zM6 21v-4H2V8h20v3.75q-.675-.35-1.412-.55t-1.513-.2q-1.95 0-3.537 1.1T13.25 15H8v4h5.1q.175.55.425 1.05t.6.95zM6 7V3h12v4z");
}

</style>
