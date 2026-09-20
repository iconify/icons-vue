<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h0e75ib7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:perc" /></template>
<style>
.h0e75ib7m {
  fill: var(--svg-color--009ba0, #009ba0);
  fill-rule: evenodd;
  d: path("M21 12a9 9 0 1 1-18 0a9 9 0 0 1 18 0m-1.588 0a7.412 7.412 0 1 1-14.824 0a7.412 7.412 0 0 1 14.824 0m-5.824 3.007v-8.83l1.589.873v8.698zm-4.764.027V6.198l1.588.873v8.698l-1.588-.74zm-2.118-3.918v3.14l1.588.698v-3.007l-1.588-.826zm9 0v3.14l1.588.698v-3.007l-1.588-.826zm-4.5-2.864v8.83l1.588.741V9.125z");
}

</style>
