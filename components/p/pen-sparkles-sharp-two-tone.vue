<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/zgwutpbmz.css';
import '../../css/z/zr5m9kbwl.css';
import '../../css/o/o6tj55oxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zgwutpbmz"/><path class="zr5m9kbwl"/><path class="o6tj55oxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pen-sparkles-sharp-two-tone" /></template>
