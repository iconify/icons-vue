<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hmxgaqb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-record-fill" /></template>
<style>
.hmxgaqb2a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 6C2 3.790861 3.790861 2 6 2L18 2C20.209139 2 22 3.790861 22 6L22 18C22 20.209139 20.209139 22 18 22L6 22C3.790861 22 2 20.209139 2 18ZM17 12C17 14.7614 14.7614 17 12 17C9.2386 17 7 14.7614 7 12C7 9.2386 9.2386 7 12 7C14.7614 7 17 9.2386 17 12Z");
}

</style>
