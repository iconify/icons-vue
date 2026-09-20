<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpf20z_qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subheader-outline-sharp" /></template>
<style>
.bpf20z_qq {
  fill: currentColor;
  d: path("M6 10h9V7H6zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
