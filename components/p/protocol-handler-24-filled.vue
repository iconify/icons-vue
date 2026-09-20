<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3p--vm-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:protocol-handler-24-filled" /></template>
<style>
.e3p--vm-d {
  fill: currentColor;
  d: path("m13.482 17.732l-.775-.775l2.482-2.482a3.5 3.5 0 0 0 0-4.95l-2.482-2.482l.775-.776a2.5 2.5 0 0 1 3.535 0l3.965 3.965a2.5 2.5 0 0 1 0 3.535l-3.965 3.965a2.5 2.5 0 0 1-3.535 0m1-3.965a2.5 2.5 0 0 0 0-3.535l-3.965-3.965a2.5 2.5 0 0 0-3.535 0l-3.965 3.965a2.5 2.5 0 0 0 0 3.535l3.965 3.965a2.5 2.5 0 0 0 3.535 0z");
}

</style>
