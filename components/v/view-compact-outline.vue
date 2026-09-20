<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkkh1bbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-compact-outline" /></template>
<style>
.wkkh1bbil {
  fill: currentColor;
  d: path("M2.962 18.904V5.096h18.077v13.808zm1-9.538H7.23v-3.27H3.96zm4.269 0H11.5v-3.27H8.23zm4.269 0h3.27v-3.27H12.5zm4.27 0h3.269v-3.27h-3.27zm0 4.268h3.269v-3.268h-3.27zm-4.27 0h3.27v-3.268H12.5zm-4.27 0h3.27v-3.268H8.23zm-1-3.269H3.963v3.27H7.23zm9.54 7.539h3.269v-3.27h-3.27zm-4.27 0h3.27v-3.27H12.5zm-4.27 0h3.27v-3.27H8.23zm-4.268 0H7.23v-3.27H3.96z");
}

</style>
