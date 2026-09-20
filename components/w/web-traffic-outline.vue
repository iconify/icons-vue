<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8v2z8bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:web-traffic-outline" /></template>
<style>
.k8v2z8bpp {
  fill: currentColor;
  d: path("M2 11.5v-1h3v1zm3.054 5.666l-.708-.72l2.1-2.1l.72.708zm1.392-9.512l-2.1-2.1l.708-.72l2.112 2.112zM16.962 18.5l-4.443-4.442l-.942 2.903l-2.193-7.23l7.308 2.192l-2.892 1.03l4.354 4.355zM10.116 6V3h1v3zm4.669 1.654l-.72-.708l2.112-2.111l.708.707z");
}

</style>
