<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qh-3y5b_g.css';
import '../../css/y/yfn9xdb5n.css';
import '../../css/j/jjar52fez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="qh-3y5b_g"/><path class="yfn9xdb5n"/><path class="jjar52fez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifer-zoom-out-linear" /></template>
