<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj-zf_bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-comfy-outline-sharp" /></template>
<style>
.fj-zf_bna {
  fill: currentColor;
  d: path("M2 20V4h20v16zm18-9V6H4v5zm-10 7h10v-5H10zm-6 0h4v-5H4z");
}

</style>
