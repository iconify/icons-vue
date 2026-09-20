<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsy82xb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:schedule-send-outline-rounded" /></template>
<style>
.xsy82xb5l {
  fill: currentColor;
  d: path("M4.192 17.315v-10.7q0-.453.361-.693q.36-.24.764-.058L14.966 10q.244.101.296.298t-.023.375t-.25.28q-.176.103-.439-.001L5.192 7v3.885l2.274.524q.236.06.354.22t.119.367t-.119.373t-.354.221l-2.274.525V17l5.13-2.171q.224-.104.395-.01q.171.093.247.268q.077.175.025.371q-.052.197-.297.298L5.323 18.06q-.404.18-.767-.056t-.364-.69m9.78 2.137q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164t1.165 2.836q0 1.67-1.165 2.835t-2.835 1.165t-2.836-1.165m3.22-2.989v-2.347q0-.154-.111-.269q-.112-.115-.273-.115t-.273.115t-.112.27v2.332q0 .153.056.297q.056.143.187.274l1.519 1.52q.111.111.263.12q.152.01.283-.12t.13-.274t-.13-.273zM9.444 12");
}

</style>
