<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfdi_ciks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-fountain-pen-outline-sharp" /></template>
<style>
.vfdi_ciks {
  fill: currentColor;
  d: path("M8.214 15.135L6.289 7.25L12 2l5.692 5.25l-1.925 7.885zm.786-1h5.98l1.603-6.537L12.5 3.823v3.843q.312.153.512.442t.2.661q0 .494-.359.853T12 9.981q-.513 0-.872-.359t-.359-.853q0-.373.2-.671t.531-.433V3.823L7.417 7.598zM5 20l.827-2.308h12.346L19 20z");
}

</style>
