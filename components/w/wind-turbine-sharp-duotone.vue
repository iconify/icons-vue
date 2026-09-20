<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/e/e3r7v46by.css';
import '../../css/l/lsal2z6ms.css';
import '../../css/b/b19wae8jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e3r7v46by"/><path class="lsal2z6ms"/><path class="b19wae8jl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wind-turbine-sharp-duotone" /></template>
