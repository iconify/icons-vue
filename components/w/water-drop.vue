<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5-me_byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-drop" /></template>
<style>
.f5-me_byk {
  fill: currentColor;
  d: path("M12.217 18.692q.223-.025.35-.15q.125-.127.125-.311q0-.216-.148-.332t-.363-.091q-1.025.075-2.29-.64q-1.266-.714-1.566-2.39q-.05-.236-.166-.353q-.117-.117-.295-.117q-.197 0-.335.147t-.083.44q.387 2.082 1.923 2.98t2.848.817M7 18.94q-2-2.063-2-5.14q0-2.154 1.738-4.765T12 3.308q3.525 3.117 5.262 5.728Q19 11.646 19 13.8q0 3.077-1.999 5.139T12 21t-5.001-2.061");
}

</style>
