<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aak7jg1_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-bottom-contract-20-filled" /></template>
<style>
.aak7jg1_u {
  fill: currentColor;
  d: path("m10.5 11.174l.874-.998a.5.5 0 0 1 .752.658l-1.75 2a.5.5 0 0 1-.752 0l-1.75-2a.5.5 0 1 1 .752-.658l.874.998V7.495a.5.5 0 1 1 1 0zM4 4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zM3 6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v5h-3.834a1.5 1.5 0 0 1-.287.493l-1.75 2a1.5 1.5 0 0 1-2.258 0l-1.75-2A1.5 1.5 0 0 1 6.834 11H3z");
}

</style>
