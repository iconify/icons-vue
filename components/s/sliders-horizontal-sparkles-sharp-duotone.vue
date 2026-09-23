<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/c/cdvt0cjgt.css';
import '../../css/r/r-7n0qcfw.css';
import '../../css/s/snibgdcaa.css';
import '../../css/s/skqfcdqhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cdvt0cjgt"/><path class="r-7n0qcfw"/><path class="snibgdcaa"/><path class="skqfcdqhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-horizontal-sparkles-sharp-duotone" /></template>
