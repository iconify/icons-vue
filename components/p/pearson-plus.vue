<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ldj4okq0c"/><path class="o3mtb7_4c"/><circle class="d2hcaxbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pearson-plus" /></template>
<style>
.d2hcaxbth {
  cx: 22.465px;
  cy: 35.593px;
  r: 0.75px;
  fill: currentColor;
}

.ldj4okq0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.362 41.642c7.73-2.41 13.231-9.813 14.249-17.708c.561-4.352-.003-9.2-3.032-12.609c-3.342-3.76-8.385-5.69-13.406-5.819c-5.823-.15-11.585 2.485-15.064 7.116c-3.4 4.524-4.603 10.446-3.535 15.99c.92 4.77 3.298 9.542 7.623 11.999c3.932 2.233 8.904 2.36 13.165 1.032z");
}

.o3mtb7_4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.511 18.024c16.92-14.914 31.772 8.963 8.954 10.228m0-8.648v11.739");
}

</style>
