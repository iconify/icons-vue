<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx0u17b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pan-tool-outline-sharp" /></template>
<style>
.zx0u17b7c {
  fill: currentColor;
  d: path("M9.59 21.5L2.72 11.433l.936-.92L8 13.538v-8.98h1v10.907l-4.411-3.081L10.12 20.5H19V5h1v16.5zm2.083-10V2.558h1V11.5zm3.673 0V3.558h1V11.5zM12.673 16");
}

</style>
