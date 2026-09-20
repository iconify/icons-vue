<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbi2vil0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stars-2-outline" /></template>
<style>
.zbi2vil0f {
  fill: currentColor;
  d: path("M7.966 17.883L12 15.463l4.054 2.464l-1.056-4.58l3.544-3.055l-4.669-.42L12 5.547l-1.854 4.298l-4.669.402l3.544 3.098zM6.44 20l1.47-6.275L3 9.481l6.47-.548L12 3l2.55 5.933l6.47.548l-4.912 4.244L17.578 20L12 16.66zM17.423 7.058l.448-1.88l-1.505-1.263l1.984-.161l.766-1.773l.765 1.773l1.985.161L20.36 5.18l.448 1.879l-1.692-1.002zm-5.404 4.667");
}

</style>
