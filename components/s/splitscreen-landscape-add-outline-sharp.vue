<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w33ue7bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-landscape-add-outline-sharp" /></template>
<style>
.w33ue7bkk {
  fill: currentColor;
  d: path("M13 16h5V8h-5zm-7 0h5V8H6zm13-8V6h-2V4h2V2h2v2h2v2h-2v2zM4 18V6zm-2 2V4h13v2H4v12h16v-8h2v10z");
}

</style>
