<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbh-y9blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-list-outline-rounded" /></template>
<style>
.fbh-y9blv {
  fill: currentColor;
  d: path("M3 17V7q0-.825.588-1.412T5 5h14q.825 0 1.413.588T21 7v10q0 .825-.587 1.413T19 19H5q-.825 0-1.412-.587T3 17m2-8h2V7H5zm4 0h10V7H9zm0 4h10v-2H9zm0 4h10v-2H9zm-4 0h2v-2H5zm0-4h2v-2H5z");
}

</style>
