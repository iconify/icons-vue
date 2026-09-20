<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvsbw4j5h.css';
import '../../css/c/cuyn6tgcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<defs><path id="SVGtFnCvbNU" class="vvsbw4j5h"/></defs><use href="#SVGtFnCvbNU" class="cuyn6tgcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:pie-chart" /></template>
