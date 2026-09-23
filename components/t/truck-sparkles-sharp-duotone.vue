<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/c/cdixm-bmx.css';
import '../../css/z/zr5m9kbwl.css';
import '../../css/z/zzqgx-_3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cdixm-bmx"/><path class="zr5m9kbwl"/><path class="zzqgx-_3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-sparkles-sharp-duotone" /></template>
