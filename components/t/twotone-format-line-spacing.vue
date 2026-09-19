<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0lo54m7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-format-line-spacing" /></template>
<style>
.d0lo54m7e {
  fill: currentColor;
  d: path("M10 5h12v2H10zm0 12h12v2H10zm-8.5 0L5 20.5L8.5 17H6V7h2.5L5 3.5L1.5 7H4v10zm8.5-6h12v2H10z");
}

</style>
