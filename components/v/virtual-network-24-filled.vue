<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pequl9bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:virtual-network-24-filled" /></template>
<style>
.pequl9bws {
  fill: currentColor;
  d: path("M4.474 7.369a1.001 1.001 0 0 1 1.552 1.262L3.288 12l2.738 3.37a1 1 0 0 1-1.552 1.26l-3.25-4a1 1 0 0 1 0-1.26zm13.645-.145a1 1 0 0 1 1.407.145l3.25 4a1 1 0 0 1 0 1.262l-3.25 4a1 1 0 0 1-1.552-1.262L20.712 12l-2.738-3.368a1 1 0 0 1 .145-1.407M7.5 10.75a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m4.501 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m4.5 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
