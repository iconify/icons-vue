<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5_l0kl4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:menopause" /></template>
<style>
.f5_l0kl4m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.434 12.07Q4.25 9.992 6.533 8.913q.072-.057.157-.096q.085-.038.177-.055Q9.197 7.75 12 7.75t5.133 1.012q.092.017.177.055q.085.039.157.096q2.283 1.079 4.099 3.157q.152.07.259.198q.047.057.083.122q.035.065.057.135q.023.07.031.144t.001.147t-.027.144t-.055.137t-.08.123q-.047.057-.103.105l-8.017 6.716q.035.212.035.459q0 1.75-1.75 1.75t-1.75-1.75q0-.247.035-.459l-8.017-6.716q-.114-.096-.183-.228t-.082-.281t.032-.291t.14-.257q.107-.128.259-.198m8.816-2.799q-1.723.098-3.233.653l3.233 7.114zm1.5 0v7.767l3.233-7.114q-1.51-.555-3.233-.653m-8.876 3.443l6.077 5.091l-3.301-7.262q-1.51.824-2.776 2.171m16.252 0q-1.266-1.347-2.776-2.171l-3.301 7.262z");
}

</style>
