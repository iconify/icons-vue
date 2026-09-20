<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n90nnubps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-off" /></template>
<style>
.n90nnubps {
  fill: currentColor;
  d: path("M20.846 22.204L1.392 2.75l.708-.708l19.454 19.454zM12.588 6.087q.22-.22.22-.549t-.22-.549t-.55-.22t-.548.22t-.22.55t.22.548t.549.22t.549-.22M7.616 22q-.672 0-1.144-.472T6 20.385V5.942l12 12v2.443q0 .67-.472 1.143q-.472.472-1.143.472zM18 15.066L6.029 3.088v-.25q.206-.382.571-.61Q6.966 2 7.442 2h8.942q.672 0 1.144.472T18 3.616V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31z");
}

</style>
