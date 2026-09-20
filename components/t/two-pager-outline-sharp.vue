<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll20iq3fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:two-pager-outline-sharp" /></template>
<style>
.ll20iq3fv {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h7V6H4zm9 0h7V6h-7zm-8-2h5v-2H5zm0-3h5v-2H5zm0-3h5V8H5zm9 6h5v-2h-5zm0-3h5v-2h-5zm0-3h5V8h-5zm-3 8V6z");
}

</style>
