<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nci760b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-pencil-outline" /></template>
<style>
.nci760b9h {
  fill: currentColor;
  d: path("m5 20l.473-1.317q.162-.452.533-.722t.848-.269h10.292q.477 0 .848.27t.533.72L19 20zm1.923-4.692L11.346 4h1.289l4.423 11.308zm1.458-1H15.6L12 5.128zm0 0H15.6z");
}

</style>
