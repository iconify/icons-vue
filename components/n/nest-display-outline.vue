<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w98y0jbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-display-outline" /></template>
<style>
.w98y0jbxg {
  fill: currentColor;
  d: path("M12 19q-2.475 0-4.237-.337T6 17.85V17H4.175Q3.3 17 2.7 16.35t-.525-1.525l.675-8q.05-.775.625-1.3T4.85 5h14.3q.8 0 1.375.525t.625 1.3l.675 8q.075.875-.525 1.525t-1.475.65H18v.85q0 .475-1.763.813T12 19m-7.825-4h15.65l-.675-8H4.85zM12 11");
}

</style>
