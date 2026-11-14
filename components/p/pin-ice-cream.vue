<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8f2dcbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-ice-cream" /></template>
<style>
.u8f2dcbrv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.651 21.872l5.996-10.492q.85-1.411.385-2.992q-.421-1.43-1.67-2.161Q16.008 2.561 12 2.561T6.638 6.227q-1.249.731-1.67 2.161q-.465 1.581.385 2.992l5.996 10.492q.101.178.279.279q.129.074.277.093t.292-.02q.144-.04.262-.131t.192-.221m4.941-13.061q.222.752-.052 1.439H6.46q-.274-.687-.052-1.439q.279-.952 1.171-1.387q.136-.067.236-.181q.1-.115.148-.259q.96-2.923 4.037-2.923t4.038 2.923q.047.144.147.259q.1.114.236.181q.892.435 1.171 1.387");
}

</style>
