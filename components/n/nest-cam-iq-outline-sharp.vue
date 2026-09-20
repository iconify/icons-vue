<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpxexcbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-cam-iq-outline-sharp" /></template>
<style>
.lpxexcbls {
  fill: currentColor;
  d: path("M8.73 20.52q-.401 0-.7-.3t-.3-.7h3.77v-4.095q-2.35-.221-3.925-1.924T6 9.442q0-2.501 1.749-4.25T12 3.441t4.251 1.75Q18 6.94 18 9.441q0 2.356-1.575 4.059T12.5 15.425v4.094h3.77q0 .402-.3.701t-.7.3zm6.808-7.54Q17 11.517 17 9.442t-1.463-3.537T12 4.442T8.463 5.905T7 9.442t1.463 3.538T12 14.442t3.538-1.462m-4.548-2.53q-.414-.414-.414-1.009t.414-1.008q.415-.415 1.009-.415t1.009.415t.414 1.008t-.414 1.009q-.415.415-1.009.415t-1.009-.415");
}

</style>
