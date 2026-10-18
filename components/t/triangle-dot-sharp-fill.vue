<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u77kv03kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangle-dot-sharp-fill" /></template>
<style>
.u77kv03kk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.1258 2.5144C11.5068 1.8285 12.4932 1.8285 12.8742 2.5144L22.8742 20.5144C22.9567 20.663 23 20.8301 23 21C23 21.5523 22.5523 22 22 22L2 22C1.4477 22 1 21.5523 1 21C1 20.8301 1.0433 20.663 1.1258 20.5144L11.1258 2.5144ZM14 14C14 12.8954 13.1046 12 12 12C10.8954 12 10 12.8954 10 14C10 15.1046 10.8954 16 12 16C13.1046 16 14 15.1046 14 14Z");
}

</style>
