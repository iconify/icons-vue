<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi_0-0bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sim-card-lock-outline-rounded" /></template>
<style>
.bi_0-0bii {
  fill: currentColor;
  d: path("M10 15.77h4q.367 0 .626-.26q.259-.258.259-.625v-3q0-.368-.288-.626q-.288-.259-.712-.259V9.885q0-.787-.55-1.336T12 8t-1.336.549t-.548 1.336V11q-.425 0-.713.259q-.288.258-.288.625v3q0 .368.259.626q.259.26.626.26m.885-4.77V9.885q0-.464.326-.79T12 8.77t.79.326t.326.79V11zm-4.27 10q-.69 0-1.152-.462T5 19.385V9.095q0-.324.13-.629q.132-.304.349-.522L9.944 3.48q.217-.218.522-.348q.305-.131.628-.131h6.29q.691 0 1.154.463T19 4.615v14.77q0 .69-.462 1.152T17.384 21zm0-1h10.77q.23 0 .423-.192t.192-.424V4.616q0-.231-.192-.424T17.384 4H10.85L6 8.85v10.535q0 .23.192.423t.423.192m0 0H6h12z");
}

</style>
