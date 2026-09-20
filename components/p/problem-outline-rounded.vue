<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmf6ilbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:problem-outline-rounded" /></template>
<style>
.hmf6ilbxp {
  fill: currentColor;
  d: path("M7.549 15.934q.22-.22.22-.55q0-.328-.22-.548T7 14.616t-.549.22t-.22.549t.22.549t.549.22t.549-.22m-.192-2.846q.143-.144.143-.357V8.346q0-.213-.143-.356T7 7.846t-.357.144t-.143.356v4.385q0 .213.143.357T7 13.23t.357-.143M11 14.5h6q.214 0 .357-.143T17.5 14t-.143-.357T17 13.5h-6q-.213 0-.357.143T10.5 14t.143.357t.357.143m0-4h6q.214 0 .357-.143T17.5 10t-.143-.357T17 9.5h-6q-.213 0-.357.143T10.5 10t.143.357t.357.143M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6z");
}

</style>
