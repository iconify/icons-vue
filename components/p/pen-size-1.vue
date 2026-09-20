<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omnxp7bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pen-size-1" /></template>
<style>
.omnxp7bqi {
  fill: currentColor;
  d: path("M4.975 19.025Q4.75 18.8 4.75 18.5t.225-.525l13-13q.225-.225.525-.225t.525.225t.225.525t-.225.525l-13 13q-.225.225-.525.225t-.525-.225");
}

</style>
