<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-gkbb1wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:owl-rounded" /></template>
<style>
.d-gkbb1wt {
  fill: currentColor;
  d: path("M8.23 9.693q-.21-.21-.21-.52t.21-.52t.52-.21t.52.21t.21.52t-.21.52t-.52.21t-.52-.21m6.5 0q-.21-.21-.21-.52t.21-.52t.52-.21t.52.21t.21.52t-.21.52t-.52.21t-.52-.21M12 21q-2.927 0-4.963-2.084T5 13.885V9.173q0-2.684 2.092-4.429T12 3q2.68 0 4.84 1.696T19 9.173v10.058q0 .31-.23.54t-.54.229H18q-1.558 0-2.664-1.106t-1.105-2.663v-.493q0-.25-.159-.374q-.158-.126-.341-.126t-.342.126t-.158.374v.493q0 1.315.65 2.398q.65 1.082 1.717 1.7q.26.16.195.415T15.49 21zm0-6.673q2.394 0 4.197-1.445T18 9.173q0-.952-.348-1.791q-.348-.84-.975-1.478q-1.735.108-2.956 1.296Q12.5 8.389 12.5 10.116q0 .213-.143.356q-.143.144-.357.144t-.357-.144t-.143-.356q0-1.727-1.23-2.92Q9.038 6.004 7.303 5.93q-.608.638-.956 1.465T6 9.173q0 2.264 1.803 3.709T12 14.327");
}

</style>
