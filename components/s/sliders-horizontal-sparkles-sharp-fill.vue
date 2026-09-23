<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/a2whkvbxs.css';
import '../../css/r/r_dstt7vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a2whkvbxs"/><path class="r_dstt7vl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-horizontal-sparkles-sharp-fill" /></template>
