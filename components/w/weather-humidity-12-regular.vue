<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u2t8wibuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-humidity-12-regular" /></template>
<style>
.u2t8wibuj {
  fill: currentColor;
  d: path("M7.5 10a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1zm1.25-2a.5.5 0 0 1 0 1h-5.5a.5.5 0 0 1 0-1zM9 6a.5.5 0 0 1 0 1H3a.5.5 0 0 1 0-1zM5.999 1a.5.5 0 0 1 .354.146v.001c.256.256 1.032 1.032 1.746 2.07c.359.522.714 1.129.977 1.783H7.983a9 9 0 0 0-.709-1.217A13.4 13.4 0 0 0 6 2.217a13 13 0 0 0-1.275 1.566A9 9 0 0 0 4.014 5H2.923A9.4 9.4 0 0 1 3.9 3.217a15 15 0 0 1 1.746-2.07A.5.5 0 0 1 6 1");
}

</style>
