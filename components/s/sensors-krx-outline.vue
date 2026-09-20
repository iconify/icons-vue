<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h83p82eza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sensors-krx-outline" /></template>
<style>
.h83p82eza {
  fill: currentColor;
  d: path("M4.527 17.017q-.723-1.084-1.125-2.352Q3 13.396 3 12q0-1.402.402-2.667q.402-1.266 1.125-2.35l.829.542q-.65.95-1.003 2.088Q4 10.75 4 12t.353 2.385t1.003 2.084zm3.502-1.046Q6.385 14.327 6.385 12t1.644-3.971T12 6.385t3.971 1.644T17.616 12t-1.645 3.971T12 17.616T8.029 15.97m7.238-.704Q16.616 13.92 16.616 12t-1.349-3.267T12 7.384t-3.267 1.35Q7.384 10.08 7.384 12t1.349 3.267T12 16.616t3.267-1.349m4.181 1.75l-.823-.548q.65-.95 1.013-2.085Q20 13.25 20 12t-.363-2.387t-1.012-2.088l.823-.542q.743 1.084 1.147 2.35Q21 10.598 21 12q0 1.396-.405 2.665t-1.147 2.352M12 12");
}

</style>
