<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8dah3afq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pin-end-outline" /></template>
<style>
.j8dah3afq {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v6h-2V6H4v12h10v2zm9.95-5.625L11 11.425v2.225H9V8h5.65v2H12.4l2.95 2.95zM19 20q-1.25 0-2.125-.875T16 17t.875-2.125T19 14t2.125.875T22 17t-.875 2.125T19 20");
}

</style>
