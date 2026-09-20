<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j_f9v_bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:phosphor-logo-light" /></template>
<style>
.j_f9v_bvt {
  fill: currentColor;
  d: path("M152 34H72a6 6 0 0 0-6 6v128a78.09 78.09 0 0 0 78 78a6 6 0 0 0 6-6v-66h2a70 70 0 0 0 0-140M78 62.91L133.74 162H78Zm60 82.19L82.26 46H138ZM78.28 174H138v59.73A66.1 66.1 0 0 1 78.28 174M152 162h-2V46h2a58 58 0 0 1 0 116");
}

</style>
