<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vev2zbc2e.css';
import '../../css/r/r-tfq900y.css';
import '../../css/o/or693yu9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vev2zbc2e"/><path class="r-tfq900y wm-a"/><path class="or693yu9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:palette-duo" /></template>
