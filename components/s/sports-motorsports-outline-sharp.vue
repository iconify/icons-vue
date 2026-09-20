<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izy5__8bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-motorsports-outline-sharp" /></template>
<style>
.izy5__8bp {
  fill: currentColor;
  d: path("M14 18q2.5 0 4.25-1.75T20 12q0-2.525-1.838-4.262T13.75 6q-1.45 0-2.72.352q-1.269.352-2.434 1.056l2.962 1.153q.87.368 1.406 1.14T13.5 11.4q0 1.308-.893 2.204t-2.157.896H4.204q-.108.523-.156 1.18T4 17.385V18zm-9.638-4.5H10.4q.887 0 1.493-.607T12.5 11.4q0-.629-.349-1.141t-.959-.77L7.646 8.065q-1.204 1.023-2.036 2.4q-.835 1.375-1.248 3.035M14 19H3v-2.366q0-2.565.79-4.702t2.215-3.677t3.4-2.397T13.75 5q1.489 0 2.806.548t2.307 1.492q.99.943 1.564 2.22Q21 10.537 21 12q0 1.439-.548 2.718q-.548 1.28-1.501 2.233t-2.223 1.501T14 19");
}

</style>
