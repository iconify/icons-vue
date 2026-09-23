<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/e/epepgykcc.css';
import '../../css/x/xhj1trd8o.css';
import '../../css/t/t-fa8-bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="epepgykcc"/><path class="xhj1trd8o"/><path class="t-fa8-bok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paper-bag-sparkles-sharp-duotone" /></template>
