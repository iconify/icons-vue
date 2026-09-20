<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2untlbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-off-rounded" /></template>
<style>
.c2untlbqb {
  fill: currentColor;
  d: path("M20.492 21.85L1.746 3.104q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16L21.2 21.142q.14.14.15.345t-.15.363t-.354.16t-.354-.16M12.587 6.087q.22-.22.22-.548q0-.33-.22-.55t-.548-.22q-.33 0-.55.22t-.22.55q0 .328.22.549q.22.22.55.22q.328 0 .549-.22M7.616 22q-.672 0-1.144-.472T6 20.385V5.942l12 12v2.443q0 .67-.472 1.143q-.472.472-1.143.472zM18 3.616V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v2.605q0 .54-.497.745t-.876-.174L6.357 3.417q-.105-.105-.146-.211t-.04-.231q0-.348.347-.661Q6.866 2 7.442 2h8.942q.672 0 1.144.472T18 3.616");
}

</style>
