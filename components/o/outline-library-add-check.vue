<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb7chnb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-library-add-check" /></template>
<style>
.mb7chnb3g {
  fill: currentColor;
  d: path("M20 4v12H8V4zm0-2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m-7.53 12L9 10.5l1.4-1.41l2.07 2.08L17.6 6L19 7.41zM4 6H2v14c0 1.1.9 2 2 2h14v-2H4z");
}

</style>
