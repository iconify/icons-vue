<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt1kjcbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sim-card-outline-sharp" /></template>
<style>
.rt1kjcbmt {
  fill: currentColor;
  d: path("M7.5 18.616h1v-1.424h-1zm0-3.808h1v-3.423h-1zm4 3.808h1v-3.424h-1zm0-5.808h1v-1.423h-1zm4 5.808h1v-1.424h-1zm0-3.808h1v-3.423h-1zM5 21V8.423L10.423 3H19v18zm1-1h12V4h-7.15L6 8.85zm0 0h12z");
}

</style>
