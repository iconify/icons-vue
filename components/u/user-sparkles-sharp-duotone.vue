<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/o/o61jznlym.css';
import '../../css/f/fkx2mnb9s.css';
import '../../css/f/ff9zbvbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o61jznlym"/><path class="fkx2mnb9s"/><path class="ff9zbvbzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-sparkles-sharp-duotone" /></template>
