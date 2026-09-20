<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txmeofw2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:theater-comedy-sharp" /></template>
<style>
.txmeofw2q {
  fill: currentColor;
  d: path("M7.505 21q-2.082 0-3.543-1.458Q2.5 18.083 2.5 16v-6h10v6q0 2.083-1.457 3.542T7.505 21M5.5 14.308q.329 0 .568-.24t.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24m3.555 2.974q.657-.426.714-1.09H5.231q.058.664.714 1.09t1.555.426t1.555-.426m1.013-3.214q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24M16.5 14q-.67 0-1.355-.185q-.685-.186-1.145-.519V8.5h-2.5V3h10v6q0 2.083-1.458 3.542Q18.583 14 16.5 14m-2-6.692q.329 0 .568-.24t.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24m-.27 3.4h4.54q-.097-.664-.754-1.09T16.5 9.192q-.677 0-1.444.364t-.825 1.152m4.269-3.4q.329 0 .568-.24t.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24");
}

</style>
