<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz0p_mbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tablet-mac-sharp" /></template>
<style>
.hz0p_mbcs {
  fill: currentColor;
  d: path("M4 22V2h16v20zm1-5.462h14V5.5H5zm7.54 3.27q.23-.23.23-.539t-.23-.54q-.23-.229-.54-.229t-.54.23t-.23.54t.23.539t.54.23t.54-.23");
}

</style>
