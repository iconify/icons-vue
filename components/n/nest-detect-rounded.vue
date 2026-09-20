<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj80qwbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-detect-rounded" /></template>
<style>
.nj80qwbzw {
  fill: currentColor;
  d: path("M9.5 21.5q-1.258 0-2.129-.871T6.5 18.5V4.116q0-.667.475-1.141t1.14-.475h2.77q.666 0 1.14.475t.475 1.14V18.5q0 1.258-.871 2.129T9.5 21.5m0-1q.817 0 1.409-.591q.591-.592.591-1.409t-.591-1.409T9.5 16.5t-1.409.591Q7.5 17.683 7.5 18.5t.591 1.409T9.5 20.5m7.616-3q-.667 0-1.141-.475t-.475-1.14v-7.77q0-.666.475-1.14t1.14-.475h.77q.666 0 1.14.475t.475 1.14v7.77q0 .666-.475 1.14t-1.14.475z");
}

</style>
