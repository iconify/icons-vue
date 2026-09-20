<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o43cumsrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-camera-front" /></template>
<style>
.o43cumsrt {
  fill: currentColor;
  d: path("M4.616 20q-.691 0-1.153-.462T3 18.384V7.616q0-.691.463-1.153T4.615 6h2.958l1.85-2h5.154l1.85 2h2.958q.69 0 1.152.463T21 7.616v10.769q0 .69-.463 1.153T19.385 20zm4.076-3.884h6.616v-.166q0-.875-.88-1.355q-.878-.48-2.428-.48t-2.429.48t-.879 1.355zm4.374-4.05q.434-.433.434-1.066t-.434-1.066T12 9.5t-1.066.434Q10.5 10.367 10.5 11t.434 1.066T12 12.5t1.066-.434");
}

</style>
