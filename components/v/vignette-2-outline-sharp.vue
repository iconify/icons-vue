<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygx8q3ijg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vignette-2-outline-sharp" /></template>
<style>
.ygx8q3ijg {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5zm0 0V5zm10.75-3.26q1.539-1.528 1.539-3.74T15.75 8.25T12 6.712T8.26 8.25T6.73 12t1.53 3.74q1.529 1.53 3.74 1.53t3.75-1.53m-6.796-.71q-1.262-1.26-1.262-3.028t1.26-3.02q1.258-1.251 3.026-1.251t3.03 1.255t1.261 3.017q0 1.762-1.259 3.024t-3.027 1.261q-1.767 0-3.03-1.259");
}

</style>
