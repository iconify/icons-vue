<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/ziuoucl8y.css';
import '../../css/h/hxfqxacle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ziuoucl8y"/><path clip-rule="evenodd" class="hxfqxacle"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:malaria-mixed-microscope" /></template>
