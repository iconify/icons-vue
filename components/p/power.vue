<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/si-uzntbh.css';
import '../../css/y/ypigdvbdi.css';
import '../../css/x/xdt81rb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="si-uzntbh"/><path class="ypigdvbdi"/><path class="xdt81rb6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:power" /></template>
