<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgrsfebyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sim-card-lock-outline" /></template>
<style>
.pgrsfebyl {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V8.423L10.423 3h6.962q.69 0 1.153.463T19 4.615v14.77q0 .69-.462 1.152T17.384 21zm0-1h10.769q.23 0 .423-.192t.192-.424V4.616q0-.231-.192-.424T17.384 4H10.85L6 8.85v10.535q0 .23.192.423t.423.192m0 0H6h12zM10 15.77h4q.367 0 .626-.26q.259-.258.259-.625v-3q0-.368-.288-.626q-.288-.259-.712-.259V9.885q0-.787-.55-1.336T12 8t-1.336.549t-.548 1.336V11q-.425 0-.713.259q-.288.258-.288.625v3q0 .368.259.626q.259.26.626.26m.885-4.77V9.885q0-.464.326-.79T12 8.77t.79.326t.326.79V11z");
}

</style>
