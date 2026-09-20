<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iorb_8tau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-info-rounded" /></template>
<style>
.iorb_8tau {
  fill: currentColor;
  d: path("M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v9.869q0 .67-.472 1.143q-.472.472-1.143.472zm4.74-6.182q.144-.143.144-.356v-4q0-.214-.143-.357T12 10.962t-.357.143t-.143.357v4q0 .213.143.356t.357.144t.357-.144m.077-6.846q.182-.181.182-.433t-.182-.434T12 7.923t-.434.182t-.182.433t.182.434t.434.182t.434-.182");
}

</style>
