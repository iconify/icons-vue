<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5tlkubht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-aod" /></template>
<style>
.h5tlkubht {
  fill: currentColor;
  d: path("M19 1H5v22h14zm-2 17H7V6h10zm-9-8h8v1.5H8zm1 3h6v1.5H9z");
}

</style>
