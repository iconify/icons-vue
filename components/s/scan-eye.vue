<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/p_qogjuvx.css';
import '../../css/j/jxl67pbry.css';
import '../../css/f/fqqpryb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p_qogjuvx"/><circle class="jxl67pbry"/><path class="fqqpryb5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:scan-eye" /></template>
