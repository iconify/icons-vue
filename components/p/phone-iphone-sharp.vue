<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f67mqyb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-iphone-sharp" /></template>
<style>
.f67mqyb3f {
  fill: currentColor;
  d: path("M6 22V2h12v20zm6-1.961q.31 0 .54-.23t.23-.54t-.23-.54T12 18.5t-.54.23t-.23.54t.23.539t.54.23m-5-3.5h10V5.5H7z");
}

</style>
