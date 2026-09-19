<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/y/y0pnzz87o.css';
import '../../css/g/gdr62dbcz.css';
import '../../css/l/lnplwwnva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="y0pnzz87o"/><path class="gdr62dbcz"/><path class="lnplwwnva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:soil-temperature-field" /></template>
