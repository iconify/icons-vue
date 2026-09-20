<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fofxwtbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-cam-outdoor" /></template>
<style>
.fofxwtbgs {
  fill: currentColor;
  d: path("M13.88 18.352q-.414.515-1.064.564q-.649.05-1.164-.366l-3.725-3.121q-.611-.506-1.067-1.142q-.456-.637-.68-1.393q-.236.339-.582.53q-.346.192-.752.192H3.27V6.922h1.577q.687 0 1.153.508q.467.507.495 1.232q.72-1.45 2.104-2.268t3.014-.818q.952 0 1.82.342t1.603.952l3.75 3.121q.515.43.568 1.068q.053.64-.376 1.155z");
}

</style>
