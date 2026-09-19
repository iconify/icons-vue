<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/r76wqnblr.css';
import '../../css/n/n65-fcc0i.css';
import '../../css/f/fe_ylwb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r76wqnblr"/><path class="n65-fcc0i"/><path class="fe_ylwb0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pen-tool-add" /></template>
