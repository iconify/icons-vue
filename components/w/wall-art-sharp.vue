<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-44-3bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wall-art-sharp" /></template>
<style>
.j-44-3bzm {
  fill: currentColor;
  d: path("M3 21V7h5.885L12 3.885L15.116 7H21v14zm4.5-3.5h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zm10.216-4.822q.323-.322.323-.793t-.323-.794t-.793-.322t-.793.322t-.322.793t.322.794t.793.322t.793-.322M10.138 7h3.724L12 5.139z");
}

</style>
