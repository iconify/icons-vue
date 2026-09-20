<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nha9m3-cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sensors-krx-sharp" /></template>
<style>
.nha9m3-cr {
  fill: currentColor;
  d: path("M4.527 17.017q-.723-1.084-1.125-2.352Q3 13.396 3 12q0-1.402.402-2.667q.402-1.266 1.125-2.35l.829.542q-.65.95-1.003 2.088Q4 10.75 4 12t.353 2.385t1.003 2.084zm3.502-1.046Q6.385 14.327 6.385 12t1.644-3.971T12 6.385t3.971 1.644T17.616 12t-1.645 3.971T12 17.616T8.029 15.97m11.419 1.046l-.823-.548q.675-.95 1.025-2.085Q20 13.25 20 12t-.35-2.387t-1.025-2.088l.823-.542q.743 1.084 1.147 2.35Q21 10.598 21 12q0 1.396-.405 2.665t-1.147 2.352");
}

</style>
