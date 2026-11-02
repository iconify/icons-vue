<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2rqivbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toggle-right-fill" /></template>
<style>
.k2rqivbes {
  fill: currentColor;
  d: path("M9 5h6a7 7 0 1 1 0 14H9A7 7 0 1 1 9 5m2.315 5.443a4 4 0 1 0 7.37 3.114a4 4 0 0 0-7.37-3.114");
}

</style>
