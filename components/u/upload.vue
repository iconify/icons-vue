<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch0locc9x.css';
import '../../css/v/vd3n2rbxy.css';
import '../../css/a/al_h_5jub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ch0locc9x"><path class="vd3n2rbxy"/><path class="al_h_5jub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:upload" /></template>
