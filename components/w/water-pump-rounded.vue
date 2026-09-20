<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-wklf5jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-pump-rounded" /></template>
<style>
.j-wklf5jl {
  fill: currentColor;
  d: path("M13.066 13.778q.434-.434.434-1.066q0-.4-.16-.79q-.161-.391-.682-1.153l-.33-.49q-.13-.187-.337-.187t-.339.187l-.328.481q-.522.81-.673 1.17t-.151.79q0 .615.434 1.053q.433.439 1.066.439t1.066-.434m-5.193 2.347q-1.7-1.702-1.7-4.127t1.702-4.125t4.127-1.7t4.125 1.702t1.7 4.127t-1.702 4.125t-4.127 1.7t-4.125-1.702M20.5 10.769V10.5h-1.979q-.327-1.47-1.237-2.646Q16.375 6.677 15.017 6H20.5v-.27q0-.212.144-.355t.357-.144t.356.144t.143.356v5.038q0 .213-.144.356t-.357.144q-.207 0-.321-.16q-.114-.162-.178-.34m-18 7.5v-5.038q0-.213.144-.356t.357-.144t.356.144t.143.356v.269h1.979q.327 1.47 1.236 2.646q.91 1.177 2.268 1.854H3.5v.27q0 .212-.144.356t-.357.143t-.356-.143t-.143-.357");
}

</style>
