<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8deemjgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-domain-disabled" /></template>
<style>
.o8deemjgk {
  fill: currentColor;
  d: path("M1.41 1.69L0 3.1l2 2V21h15.9l3 3l1.41-1.41zM6 19H4v-2h2zm0-4H4v-2h2zm-2-4V9h2v2zm6 8H8v-2h2zm-2-4v-2h2v2zm4 4v-2h1.9l2 2zM8 5h2v2h-.45L12 9.45V9h8v8.45l2 2V7H12V3H5.55L8 5.45zm8 6h2v2h-2z");
}

</style>
