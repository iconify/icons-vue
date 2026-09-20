<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gybhqy77l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-friendly-sharp" /></template>
<style>
.gybhqy77l {
  fill: currentColor;
  d: path("M5 22V2h12v4.923h-1V5.5H6v13h10v-1.423h1V22zm9.95-6.692l-3.558-3.558l.708-.708l2.85 2.85l5.689-5.688l.707.707z");
}

</style>
