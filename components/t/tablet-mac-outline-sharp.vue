<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dne5ugbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tablet-mac-outline-sharp" /></template>
<style>
.dne5ugbxs {
  fill: currentColor;
  d: path("M4 22V2h16v20zm1-4.461V21h14v-3.462zm0-1h14V5.5H5zM5 4.5h14V3H5zm0 0V3zm0 13.039V21zm7.54 2.27q.23-.23.23-.54t-.23-.54q-.23-.229-.54-.229t-.54.23t-.23.54t.23.539t.54.23t.54-.23");
}

</style>
