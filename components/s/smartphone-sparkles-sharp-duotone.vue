<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/iilrtq97p.css';
import '../../css/l/l9gqw4bde.css';
import '../../css/f/fmu2vzbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="iilrtq97p"/><path class="l9gqw4bde"/><path class="fmu2vzbby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-sparkles-sharp-duotone" /></template>
