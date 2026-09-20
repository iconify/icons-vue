<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhafpeb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-off-outline-rounded" /></template>
<style>
.qhafpeb2c {
  fill: currentColor;
  d: path("M20.492 21.85L1.746 3.104q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16L21.2 21.142q.14.14.15.345t-.15.363t-.354.16t-.354-.16M7.442 2h8.943q.666 0 1.14.475T18 3.614V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v3.342q0 .25-.155.375t-.341.125t-.345-.13t-.159-.376V3.616q0-.27-.173-.443T16.385 3H6q.154-.44.54-.72q.385-.28.902-.28m5.146 4.086q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22M7.616 22q-.667 0-1.141-.475T6 20.386V5.942l1 1v13.443q0 .269.173.442t.443.173h8.788q.269 0 .432-.173q.164-.173.164-.442v-3.443l1 1v2.443q0 .666-.475 1.14t-1.14.475zm6.073-11.277");
}

</style>
