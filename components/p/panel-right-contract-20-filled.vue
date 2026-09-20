<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zfjsiiszv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-right-contract-20-filled" /></template>
<style>
.zfjsiiszv {
  fill: currentColor;
  d: path("m9.179 10.5l-.998.874a.5.5 0 1 0 .658.752l2-1.75a.5.5 0 0 0 0-.752l-2-1.75a.5.5 0 1 0-.658.752l.998.874H5.5a.5.5 0 0 0 0 1zM16 16a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2H4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2zM12 5v10H4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1z");
}

</style>
