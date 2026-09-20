<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p5wwzt7iy.css';
import '../../css/k/khgtwubok.css';
import '../../css/s/seiis-bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p5wwzt7iy"/><path class="khgtwubok"/><path class="seiis-bzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:money-recive-filled" /></template>
