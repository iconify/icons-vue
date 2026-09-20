<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vbh8q0bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-contract-20-filled" /></template>
<style>
.vbh8q0bgl {
  fill: currentColor;
  d: path("M10.821 10.5H14.5a.5.5 0 0 0 0-1h-3.679l.999-.874a.5.5 0 1 0-.659-.752l-2 1.75a.5.5 0 0 0 0 .752l2 1.75a.5.5 0 1 0 .659-.752zM4 4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zm4 11V5h8a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1z");
}

</style>
