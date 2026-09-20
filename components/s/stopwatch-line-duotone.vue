<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p7p5oub5r.css';
import '../../css/p/pxm7_12cz.css';
import '../../css/u/u8gkuv4uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p7p5oub5r"/><path class="pxm7_12cz"/><path class="u8gkuv4uz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stopwatch-line-duotone" /></template>
