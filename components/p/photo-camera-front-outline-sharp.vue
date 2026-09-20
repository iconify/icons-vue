<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pba_mlhap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-camera-front-outline-sharp" /></template>
<style>
.pba_mlhap {
  fill: currentColor;
  d: path("M3 20V6h4.573l1.85-2h5.154l1.85 2H21v14zm1-1h16V7h-4.011l-1.845-2H9.856L8.012 7H4zm4.692-2.884h6.616v-.166q0-.875-.88-1.355q-.878-.48-2.428-.48t-2.429.48t-.879 1.355zm4.374-4.05q.434-.433.434-1.066t-.434-1.066T12 9.5t-1.066.434Q10.5 10.367 10.5 11t.434 1.066T12 12.5t1.066-.434");
}

</style>
