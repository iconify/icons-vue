<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsq0rcb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pin-road" /></template>
<style>
.xsq0rcb_g {
  fill: currentColor;
  d: path("M8 21v-4h2v4zm0-7v-4h2v4zm0-7V3h2v4zM2 21L4.5 3h2L4 21zm14.963-.075q-.138-.075-.213-.225l-.1-.225q-.575-1.2-1.6-2.063T13.3 16.45q-.425-.65-.625-1.375t-.2-1.475q0-1.95 1.425-3.262t3.4-1.313q1.95 0 3.325 1.4T22 13.8q0 .725-.2 1.4t-.6 1.25q-.725 1.1-1.763 1.963t-1.587 2.062l-.1.225q-.075.15-.213.225T17.25 21t-.288-.075m1.7-5.762q.588-.588.588-1.413t-.587-1.412t-1.413-.588t-1.412.588t-.588 1.412t.588 1.413t1.412.587t1.413-.587M12.35 9.025L11.5 3h2l.65 4.675q-.5.275-.95.6t-.85.75");
}

</style>
