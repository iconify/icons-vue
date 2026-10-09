<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihnl7ab7i.css';
import '../../css/k/k8yin4bou.css';
import '../../css/g/gfbmiabsc.css';
import '../../css/w/wvft85b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihnl7ab7i"/><path class="k8yin4bou"/><path class="gfbmiabsc"/><path class="wvft85b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-irradiance-48-bold" /></template>
