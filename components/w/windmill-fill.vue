<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jex0rjcgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:windmill-fill" /></template>
<style>
.jex0rjcgg {
  fill: currentColor;
  d: path("m7.707 2.293l3 2.999a3.02 3.02 0 0 1 2.586 0l3-2.999a.999.999 0 1 1 1.414 1.414l-2.999 3a3.02 3.02 0 0 1 0 2.586l2.999 3a.999.999 0 1 1-1.414 1.414l-3-2.999a3.02 3.02 0 0 1-2.586 0l-3 2.999a.999.999 0 1 1-1.414-1.414l2.999-3a3.02 3.02 0 0 1 0-2.586l-2.999-3a.999.999 0 1 1 1.414-1.414m4.74 11.813l4 2c.261.13.452.368.523.651L17.781 20H21a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h3.219l.811-3.243a1 1 0 0 1 .523-.651l4-2a1 1 0 0 1 .894 0");
}

</style>
