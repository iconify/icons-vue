<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to21_vdpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shopping-bag-sharp" /></template>
<style>
.to21_vdpc {
  fill: currentColor;
  d: path("M4 22V6h4q0-1.65 1.175-2.825T12 2t2.825 1.175T16 6h4v16zm6-16h4q0-.825-.587-1.412T12 4t-1.412.588T10 6m-2 5h2V8H8zm6 0h2V8h-2z");
}

</style>
