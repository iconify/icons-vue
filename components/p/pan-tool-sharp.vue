<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjymibmkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pan-tool-sharp" /></template>
<style>
.cjymibmkn {
  fill: currentColor;
  d: path("M9.59 21.5L2.72 11.433l.936-.92L8 13.538v-8.98h1V11.5h2.673V2.558h1V11.5h2.673V3.558h1V11.5H19V5h1v16.5z");
}

</style>
