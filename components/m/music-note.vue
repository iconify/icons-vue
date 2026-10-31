<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/g/gvg1y4b0c.css';
import '../../css/k/khtt72elu.css';
import '../../css/t/t2x9xbbmy.css';
import '../../css/w/w34xigtyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="gvg1y4b0c wm-shadow"/><path class="khtt72elu wm-shadow"/><path class="t2x9xbbmy"/><path class="w34xigtyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:music-note" /></template>
