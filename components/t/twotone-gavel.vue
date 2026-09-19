<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpldkib_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-gavel" /></template>
<style>
.tpldkib_s {
  fill: currentColor;
  d: path("M1 21h12v2H1zM5.24 8.07l2.83-2.83l14.14 14.14l-2.83 2.83zM12.32 1l5.66 5.66l-2.83 2.83l-5.66-5.66zM3.83 9.48l5.66 5.66l-2.83 2.83L1 12.31z");
}

</style>
