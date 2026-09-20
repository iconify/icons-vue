<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn-mx6brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vital-signs-outline-sharp" /></template>
<style>
.fn-mx6brv {
  fill: currentColor;
  d: path("M2.039 12.5v-1h5.238l2.146 5.446l5.154-12.613l2.892 7.167H22v1h-5.238l-2.185-5.466l-5.173 12.614L6.569 12.5z");
}

</style>
