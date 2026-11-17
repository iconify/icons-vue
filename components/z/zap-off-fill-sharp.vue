<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt4o0-wqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-fill-sharp" /></template>
<style>
.wt4o0-wqb {
  fill: currentColor;
  d: path("M16.275 15.032L8.826 7.584l4.141-5.207A1.002 1.002 0 0 1 14.75 3v6H19a1 1 0 0 1 .783 1.623ZM2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414l-4.524-4.524l-2.736 3.44A1.002 1.002 0 0 1 9.25 21v-6H5a1 1 0 0 1-.783-1.623l2.103-2.643l-5.027-5.027a.999.999 0 1 1 1.414-1.414");
}

</style>
