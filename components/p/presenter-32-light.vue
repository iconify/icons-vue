<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bbu_cub_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presenter-32-light" /></template>
<style>
.bbu_cub_o {
  fill: currentColor;
  d: path("M26.97 16a1.03 1.03 0 0 1 .797 1.684l-.069.075L21 24.457v2.293A3.25 3.25 0 0 1 17.75 30h-3.5A3.25 3.25 0 0 1 11 26.75v-2.293l-6.698-6.698A1.031 1.031 0 0 1 5.03 16zM5.03 17a.03.03 0 0 0-.021.052l6.845 6.845a.5.5 0 0 1 .146.353v2.5A2.25 2.25 0 0 0 14.25 29h3.5A2.25 2.25 0 0 0 20 26.75v-2.5a.5.5 0 0 1 .146-.354l6.845-6.844l.009-.022a.03.03 0 0 0-.009-.021L26.97 17zm13.22-6a3.25 3.25 0 0 1 3.25 3.25v.25h-1v-.25A2.25 2.25 0 0 0 18.25 12h-4.5a2.25 2.25 0 0 0-2.25 2.25v.25h-1v-.25A3.25 3.25 0 0 1 13.75 11zM16 2a3.75 3.75 0 1 1 0 7.5A3.75 3.75 0 0 1 16 2m0 1a2.75 2.75 0 1 0 0 5.5A2.75 2.75 0 0 0 16 3");
}

</style>
