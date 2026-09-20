<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe4v-rr6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-android" /></template>
<style>
.pe4v-rr6t {
  fill: currentColor;
  d: path("M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v9.869q0 .67-.472 1.143q-.472.472-1.143.472zm4.972-2.99q.22-.22.22-.549q0-.328-.22-.548t-.55-.22t-.548.22t-.22.549t.22.549t.549.22t.549-.22");
}

</style>
