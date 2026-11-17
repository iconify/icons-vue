<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6ifz7bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-fill" /></template>
<style>
.e6ifz7bju {
  fill: currentColor;
  d: path("M16.275 15.032L8.826 7.584l3.519-4.424A1.35 1.35 0 0 1 14.75 4v5H18a1.483 1.483 0 0 1 1.16 2.405ZM2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414l-4.524-4.524l-2.114 2.657A1.35 1.35 0 0 1 9.25 20v-5H6a1.483 1.483 0 0 1-1.16-2.405l1.48-1.861l-5.027-5.027a.999.999 0 1 1 1.414-1.414");
}

</style>
